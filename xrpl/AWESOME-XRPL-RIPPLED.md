
******

## `1.2 XRPL RIPPLED`


##### <sup>*TOC*</sup> [🏠](/README.md) <sup>*1.1 Overview*</sup>[👇](/xrpl/AWESOME-XRPL.md) <sup>*1.2 Rippled*</sup>✋🏿 <sup>*1.3 cryptography*</sup>[👇](/xrpl/AWESOME-XRPL-CRYPTOGRAPHY.md) <sup>*1.4 client*</sup>[👇](/xrpl/AWESOME-XRPL-SOFTWARE.md) <sup>*1.5 ecosystem*</sup>[👇](/xrpl/AWESOME-XRPL-ECOSYSTEM.md) <sup>*1.6 web3*</sup>[👇](/xrpl/AWESOME-XRPL-WEB3.md) <sup>*1.7 sidechains*</sup>[👇](/xrpl/AWESOME-XRPL-SIDE.md)

<br/>

  - [Features 🗝️](#1-xrpfeat)
  - [Validators 🗝️](#1-xrpnode)
  - [Rippled software 🗝️](#1-rippled)



## 
###### <sub>*1-xrpfeat*</sub>🚪
### Xrpl Feature<sup>*[ds]$*</sup> [{✘}](https://xrpl.org/concepts.html) 
︻╦̵̵̿╤─ ҉~•

  - **Standards / drafts Proposals**
    - **XRPLF/XLS-#.#d** [👨](https://github.com/XRPLF/XRPL-Standards/discussions) [🧱](https://github.com/XRPLF/XRPL-Standards) <sub>*Xrp Ledger Standards / drafts*</sub>
    - **XRPLF/pulls** [👨](https://github.com/XRPLF/rippled/pulls) **XRPLF/issues** [👨](https://github.com/XRPLF/rippled/issues)
    - **opensource/ripple** [📖](https://opensource.ripple.com/docs/) [🧱](https://github.com/ripple/opensource.ripple.com) <sub>***NEW Projects***</sub>
    - []()
    - **Amendments**
       - [{✘}](https://xrpl.org/amendments.html) [{✘}](https://xrpl.org/contribute-code.html)
       - **list** [🇦](https://xrpl.org/known-amendments.html) [🇦](https://xrpscan.com/amendments) [🇦](https://bithomp.com/amendments)
         - onledger.net stats [📝](https://docs.google.com/spreadsheets/d/1rYiEJMwiXdpRvt4hTyy3D8qfcpVxWc0LYbyKc7gP_lA/edit#gid=0) [🇦](https://onledger.net/)  <sub>*Metrics/Amend Status*</sub>
       - XLS-11d [👨](https://github.com/XRPLF/XRPL-Standards/discussions/19) <sub>*Retiring Amendments*</sub>
       - 2023.10 Daniel_wwf [🐦](https://twitter.com/daniel_wwf/status/1709419048084054420) [📝](/xrpl/Rippled/features/Daniel_wwf-Amendment-Process101-2023.10.pdf) [📝](/xrpl/Rippled/features/daniel_wwf-SOTS-proposal-turn-into-amendment-2023.10.md) [📝](/xrpl/Rippled/features/daniel_wwf-voting-amendments-2023.10.md)
       - 2023.09 JTXRP_AGWJames [🐦](https://twitter.com/JTXRP_AGWJames/status/1707574807162744871)
  - []()
  - **Features**
      - **Consensus Protocol** [{✘}](https://xrpl.org/consensus.html)
        - [▶️](https://youtu.be/lP63dTY_7j0) [▶️](https://youtu.be/QxbsWPuJSTg) 🔥 
        - [📝](https://github.com/XRPLF/rippled/blob/develop/docs/consensus.md) <sup>[📝](https://ripple.com/files/ripple_consensus_whitepaper.pdf)</sup>[🏬](https://icedrive.net/s/SNXXY6auCxkQ9GS6aTTxu1vbXyCA) <sup>[📝](ghassankarame.com/ripple.pdf)</sup> [📝](https://github.com/vardantandon/ripple-consensus-protocol-evaluation) 🔥
        - <sup>[📝](https://coinbrain.com/dictionary/xrp-ledger-consensus-mechanism-explained-in-simple-terms)</sup> [📝](https://www.bots.io/botspedia/ripple-how-it-works-and-why-it-is-different-than-other-crypto) [📝](https://www.geeksforgeeks.org/how-does-ripple-control-protocol-algorithm-work/) [📝](https://www.educative.io/answers/how-does-the-ripple-protocol-consensus-algorithm-rpca-work) <sup>[📝](https://blog.netcoins.com/understanding-xrps-consensus-protocol-how-it-differs-from-bitcoins-proof-of-work/)</sup> 🔥
        - 2023.11 daniel_wwf [📝](/xrpl/Rippled/consensus/daniel_wwf-Understanding-Byzantine-Generals-2023.11.md)
      - []()
      - Source/Destination Tags ***`see also xaddress`***[👇](/xrpl/AWESOME-XRPL-CRYPTOGRAPHY.md#1-xrpalg)
        - 2023.09 daniel_wwf [🐦](https://twitter.com/daniel_wwf/status/1705577238668656837)
      - Fees [📝](/xrpl/Rippled/features/FeeEscalation.md)
        - XRPFees [🇦](https://xrpl.org/known-amendments.html#xrpfees) #4247[👨](https://github.com/XRPLF/rippled/pull/4247) [{§}](https://xrpl.org/blog/2023/rippled-1.10.0.html) [{✘}](https://xrpl.org/transaction-cost.html#special-transaction-costs) <sub>*Fee setting and handling improvements*</sub>
  - []()
  - **Advanced Features**
      - []()
      - **Multisigning** [{✘}](https://xrpl.org/multi-signing.html) [{✘}](https://xrpl.org/set-up-multi-signing.html) [▶️](https://youtu.be/1NdRgxvgZAA)
        - ExpandedSignerList <sup>*1-to-32*</sup>[🇦](https://xrpl.org/known-amendments.html#expandedsignerlist) [{✘}](https://xrpl.org/multi-signing.html#wallet-locator) 
        - wietse/XRPL-MultiSignTool [🧱](https://github.com/WietseWind/XRPL-MultiSignTool)
        - *Transaction specific Signer Quorum* <sup>📡 XLS-31d[👨](https://github.com/XRPLF/XRPL-Standards/discussions/77)</sup>
      - []()
      - **Regular-Key (alt-key)** [{✘}](https://xrpl.org/assign-a-regular-key-pair.html) [▶️](https://youtu.be/7JLMuYoI1u8)
      - []()
      - **Payment-Channels** [{✘}](https://xrpl.org/payment-channels.html) [{✘}](https://xrpl.org/use-payment-channels.html) [▶️](https://youtu.be/sk5VtP0Vhps) [▶️](https://youtu.be/35NcPi25D_Q) [▶️](https://youtu.be/zjha7XgcuME)  
      - []()
      - **Tickets** [{✘}](https://xrpl.org/tickets.html) [{✘}](https://xrpl.org/use-tickets.html) <sup>*xls-13d[👨](https://github.com/XRPLF/XRPL-Standards/discussions/18)*</sup>
        - example: **XRPL-Labs/Parallel-Payment-Service** [🧱](https://github.com/XRPL-Labs/Parallel-Payment-Service) <sub>*Multi TX Sender - submitting multiple transactions in parallel*</sub>
      - []()
      - **Checks** [{✘}](https://xrpl.org/checks.html) [{✘}](https://xrpl.org/use-checks.html) [🇦​](https://xrpl.org/known-amendments.html#checks)
      - []()
      - **Escrow** [{✘}](https://xrpl.org/escrow.html) [{✘}](https://xrpl.org/escrow-uc.html) [{✘}](https://xrpl.org/use-escrows.html) #fix1523 [🇦](https://xrpl.org/known-amendments.html#fix1523) [🧱](https://github.com/XRPLF/xrpl-dev-portal/tree/master/content/_code-samples/escrow) <sub>*native smart-contracts*</sub>
        - **Conditional Escrow** [{✘}](https://xrpl.org/send-a-conditionally-held-escrow.html) [📝](https://datatracker.ietf.org/doc/html/draft-thomas-crypto-conditions-02#section-8.1) [🧱](https://github.com/interledgerjs/five-bells-condition)
          - Tutorial <sub>*D.Dawson*</sub> [▶️](https://youtu.be/jUQ2nM5JXjc) [{✘}](https://xrpl.org/create-conditional-escrows-using-javascript.html) 
            > <sub>*[Quickstart dir](https://github.com/XRPLF/xrpl-dev-portal/tree/master/content/_code-samples/quickstart/js/), npm install five-bells-condition, node getConditionAndFulfillment.js*</sub>
        - 
      - []()
      - *More...*[{✘}](https://xrpl.org/payment-types.html)
      - []()
      - **Clawback** [{✘}](https://xrpl.org/clawback.html) [{✘}](https://xrpl.org/clawing-back-tokens.html) [📝](https://dev.to/ripplexdev/enhancing-trust-and-safety-with-the-clawback-feature-on-the-xrp-ledger-k6b) <sup>XLS-0039d</sup>[👨](https://github.com/XRPLF/XRPL-Standards/tree/master/XLS-0039d-clawback) [👨](https://github.com/XRPLF/XRPL-Standards/discussions/94)
        - 2023.10 lachlanalextodd [📝](/xrpl/Rippled/features/lachlanalextodd-Xrpl-Clawback-2023.10.md)
        - 2023.10 daniel_wwf [📝](/xrpl/Rippled/features/daniel_wwf-clawback-2023.10.md) [📝](https://www.reddit.com/r/XRP/comments/179zgk0/freezing_and_clawback_on_the_xrpl/) <sub>*[📝](https://www.straitsx.com/blog-post/straitsx-insights-19-protecting-asset-stability-and-users-with-asset-clawback) [🐦](https://twitter.com/JoelKatz/status/1709269004668596255) [{✘}](https://xrpl.org/freezes.html)*</sub>
        - 2023.10 sologenic [📝](https://sologenic.medium.com/the-xrpl-clawback-feature-a-game-changer-for-institutional-investors-59e4e7bc7698)
      - []()
      - ***XLS-42d Plugins - Mayukha Vadari [🐦](https://twitter.com/msvadari)*** <sup>📡</sup>[👨](https://github.com/XRPLF/XRPL-Standards/discussions/116) ~~closed [👨](https://github.com/XRPLF/XRPL-Standards/discussions/113)~~ [🧱](https://github.com/mvadari/xrpl-plugin) [▶️](https://youtu.be/FDqJ-5QKUEU)
      - []()
      - ***XLS-48d Document Storage*** <sup>📡</sup>[👨](https://github.com/XRPLF/XRPL-Standards/discussions/132)
  - []()
  - ***`Web3 Features`*** [👇](/xrpl/AWESOME-XRPL-WEB3.md)
  - []()
  - ***`Xahau Features`*** [👇](/xrpl/AWESOME-XRPL-SIDE.md#1-xrpxah) 
  - []()



<br><br>

## 
###### <sub>*1-xrpnode*</sub>🚪
### Xrpl Servers, Nodes & Validators [🖼](/xrpl/Rippled/Rippled-nodes-2023-10-29.png)

  - ***`see also wojake notes 👉`*** [🧱](https://github.com/wojake/awesome-xrpl#i-want-to-run-a-node-%EF%B8%8F)
  - []()
  - **Run a Rippled Node**  
      - wietse/docker-rippled <sup>go shell dockerfile</sup>[🧱](https://github.com/WietseWind/docker-rippled) [🌎](https://hub.docker.com/r/xrpllabsofficial/xrpld) <sub>*Run a rippled node in a Docker container*</sub>
      - **Guides**
        - [{✘}](https://xrpl.org/xrpl-servers.html) [{✘}](https://xrpl.org/infrastructure.html)
          - 2023.09 wietse (APEX) Infrastructure Overhaul [▶️](https://youtu.be/_zkA481dyS4) [🎆](https://blog.xumm.app/infra)
        - []()
        - [📝](https://xrpcommunity.blog/rippled/) [📝](https://nownodes.io/blog/how-to-run-a-ripple-node/) [📝](https://somsubhra.com/how-to-setup-a-ripple-node/) [📝](https://www.reddit.com/r/XRP/comments/o9gn00/running_a_node/) <sup>[▶️](https://www.youtube.com/watch?v=8ibAAgGtlB4)</sup>[📝](https://timrowley.net/xrpl-node-setup-on-aws-95f3ee6de135) 🔥 [📝](https://www.xrpchat.com/topic/39369-tired-to-maintenance-a-ripple-node-and-need-some-help/) [📝](https://medium.com/@xspectarnft/xspectar-xrpl-nodes-how-to-785442c35ff2)
        - [▶️](https://youtu.be/PxStbjrsNjQ) [▶️](https://youtu.be/LrG8EXSOX5s) [▶️](https://youtu.be/Cf-a6aaS7lI) [▶️](https://youtu.be/kEsvSUf1CX4) [🔽](https://youtu.be/par2uVsnR90) 🔥 [🔽](https://youtu.be/0-871XWa7qI)
        - [👨](https://github.com/XRPLF/rippled/issues/4713) [👨](https://github.com/XRPLF/rippled/discussions/4433#discussioncomment-5104098) [👨](https://github.com/XRPLF/rippled/discussions/4433)
        - []()
        - The machine <sup>[*`(recommended Linux OS)`*](/web3dev/AWESOME-WEBSYS.md#--linux-)</sup>
           - Raspberry Pi4
              - [🌎](https://write.as/dvilela/) [📖](/xrpl/Rippled/validators/dvilela-xrpl-validator-raspberry.zip) [🧱](https://github.com/dvilelaf/xrpldRaspberryPi)
           - <sub>Centos [🔽](https://youtu.be/QfCMecK1Bi0) [🔽](https://youtu.be/GxPonERUfXM) [🔽](https://youtu.be/qzSKmtcrhtI)</sub>
      - []()
      - xrplf.github.io/xrpl-node-configurator [{✘}](https://xrplf.github.io/xrpl-node-configurator/#/)
        - example [🧱](https://github.com/XRPLF/rippled/blob/7bd5d51e4e4e76a5547051d30b330739618eddb0/cfg/rippled-example.cfg)
      - []()
      - 3rd Party Services
        - [🌎](https://www.quicknode.com/chains/xrpl)
  - []()
  - **Validators**
      - **list** [🌎](https://xrpscan.com/validators) [🌎](https://bithomp.com/validators) [{✘}](https://livenet.xrpl.org/network/validators) [🌎](https://www.digitalvalidity.com/)
        - [🌎](https://onledger.net/) <sub>*Metrics/Validators*</sub>
        - <sub>*some validators &emsp; <sup>[🐦](https://twitter.com/alloynetworks) 🇪🇪</sup>[🌎](https://www.alloy.ee/) &emsp; <sup>🇳🇱</sup>[🌎](https://validator.xrpl-labs.com) &emsp; <sup>[🐦](https://twitter.com/jonaagenilsen) 🇳🇴</sup>[🌎](https://jon-nilsen.no/) &emsp; <sup>[🐦](https://twitter.com/ftso_eu/) 🇮🇹</sup>[🌎](https://xrpvalidator.ftso.eu/) &emsp; <sup>[🐦](https://twitter.com/ekiserrepe) 🇪🇸</sup>[🌎](https://ekiserrepe.com/) &emsp; 🔥 &emsp; <sup>[🖼](/xrpl/Rippled/validators/onledger.net.png) [🐦](https://twitter.com/offledger) 🇳🇿</sup>[🌎](https://onledger.net/) &emsp; <sup>[🐦](https://twitter.com/XRPL_rabbit) 🇺🇸</sup>[🌎](https://rabbitkick.club/) &emsp; <sup>[🐦](https://twitter.com/ShortTheFomo) 🇫🇮</sup>[🌎](https://panicbot.app/) &emsp; <sup>🇨🇩</sup>[🌎](https://pingonce.com/) &emsp; <sup>[🐦](https://twitter.com/Multi_Hop) 🇬🇷</sup>[🌎](https://multi-hop.xyz/)*</sub>
      - wietse/docker-rippled-validator <sup>go shell dockerfile</sup>[🧱](https://github.com/WietseWind/docker-rippled-validator) <sub>*Run a Ripple XRP (rippled) validator in a Docker container*</sub>
      - guides
        - [{✘}](https://xrpl.org/run-rippled-as-a-validator.html) [▶️](https://youtu.be/mJCJUTpwnNM) 
        - otter [🧱](https://github.com/OtterServices/RippledValidatorGuide/) [📖](/xrpl/Rippled/validators/XRP_Ledger_Linux_Validator_Initialization_Guide_V1.pdf)
        - rabbitkick [🌎](https://rabbitkick.club/) [📖](/xrpl/Rippled/validators/rabbitkick.club-running-rippled.zip)
           - [🔽](https://youtu.be/c-VDS-66NDM) [🔽](https://youtu.be/H5fnAHfzTsE) [🔽](https://youtu.be/dXjxE-KOuYg) [🔽](https://youtu.be/M5-0fXPhFm8)
      - []()
      - 2023.08 daniel_wwf [📝](/xrpl/Rippled/validators/daniel_wwf-No-incentive-2023.08.md) <sub>*[▶️](https://youtu.be/fo8ZScrXFZE)*</sub>
      - 2023.09 D.Schwartz [📝](/xrpl/Rippled/validators/joelkatz-DSchwartz-what-validators-do-2023.09.md)
      - 2023.10 daniel_wwf [📝](/xrpl/Rippled/validators/daniel_wwf-What-are-Validators-2023.10.07.md)
  - []()
  - **XRPL CLUSTER**
    - xrplcluster.com ws-stats.com [🌎](https://xrplcluster.com/) [🌎](https://xrpl.ws-stats.com/) [🧱](https://github.com/XRPLF/XRPL-Cluster.com) [{✘}](https://xrpl.org/clustering.html) [{✘}](https://xrpl.org/cluster-rippled-servers.html)
    - 2023.10 Daniel_wwf [🐦](https://twitter.com/daniel_wwf/status/1708618261330280552) [📝](/xrpl/Rippled/daniel_wwf-Whatis-XRPL-CLUSTER-2023.10.pdf)
  - []()
  - **CLIO SERVER** <sup>c++</sup> <sub>*can help reduce the load on rippled servers running in p2p mode*</sub>  
    - docs [{✘}](https://xrpl.org/blog/2022/introducing-clio.html) [{✘}](https://xrpl.org/the-clio-server.html) [{✘}](https://xrpl.org/manage-the-clio-server.html)
    - software [🧱](https://github.com/XRPLF/clio) [🧱](https://github.com/XRPLF/clio-packages) 
 - []()





<br><br>






## 
###### <sub>*1-rippled*</sub>🚪
### Rippled Server Dæmon

  - ***`see also xrpl cryptography`*** [👇](/xrpl/AWESOME-XRPL-CRYPTOGRAPHY.md)
  - ***`see also xrpl client software`*** [👇](/xrpl/AWESOME-XRPL-SOFTWARE.md)
  - []()
  - **XRPLF/rippled** <sup>c++ linux/mac/windows</sup>[🧱](https://github.com/XRPLF/rippled) [{✘}](https://xrplf.github.io/rippled/) <sub>*Rippled Server Software for the XRP Ledger*</sub>
    - */pulls* [👨](https://github.com/XRPLF/rippled/pulls) */issues* [👨](https://github.com/XRPLF/rippled/issues)
    - **RELEASES** [🧱](https://github.com/XRPLF/rippled/releases)
  - core-ledger <sup>prj</sup>[🧱](https://github.com/orgs/XRPLF/projects/1)
  - Rippled Source Code Guide <sup>v1.5 xrpintel</sup>[🌎](https://xrpintel.com/source) [📁](/xrpl/Rippled)  
  - []()
  - **XrplLabs/ripple ledger-tools** <sub>*for service administrators*</sub>
    - xrpl-tools [{✘}](https://xrpl.org/dev-tools.html)
      - xrp-ledger.toml Checker [{✘}](https://xrpl.org/xrp-ledger-toml-checker.html)
      - validator-domain-verifier [{✘}](https://xrpl.org/validator-domain-verifier.html)
      - xrp-ledger-rpc [{✘}](https://xrpl.org/xrp-ledger-rpc-tool.html)
      - websocket-api [{✘}](https://xrpl.org/websocket-api-tool.html)
    - XRPLF/Supply-Calculator <sup>*js xrpl-client sqlite*</sup>[🧱](https://github.com/XRPLF/Supply-Calculator)
    - []()
    - xpring-eng/xrpl-validator-domains <sup>js/ts</sup>[🧱](https://github.com/xpring-eng/xrpl-validator-domains)
    - xpring-eng/rippled-network-crawler <sup>js</sup>[🧱](https://github.com/xpring-eng/rippled-network-crawler)
    - []()
    - **Wietse**
      - wietse/rippled-ws-client-dashboard [🧱](https://github.com/WietseWind/rippled-ws-client-dashboard) xrp.fans[🌎](https://xrp.fans/) <sub>*Dashboard Debugging & Dev 4 xrpl*</sub>
      - wietse/fetch-xrpl-transactions <sup>*Google BigQuery*</sup>[🧱](https://github.com/WietseWind/fetch-xrpl-transactions)
      - wietse/xrpl-accountinfo [🧱](https://github.com/WietseWind/fetch-xrpl-accounts) <sub>*Fetch all the XRP ledger accounts*</sub>
      - wietse/xrpl-stats [🧱](https://github.com/WietseWind/xrp-ledgerstats)
    - []()
    - **Richard**
      - /xrpl-tools
        - richard/memo-pow-benchmark [🧱](https://github.com/RichardAH/xrpl-tools/tree/master/memo-pow-benchmark)
        - richard/peer-connection [🧱](https://github.com/RichardAH/xrpl-tools/tree/master/peer-connection)
        - richard/validator-address-tool [🧱](https://github.com/RichardAH/xrpl-tools/tree/master/validator-address-tool)
      - richard/xrpl-fetch-unl <sup>js</sup>[🧱](https://github.com/RichardAH/xrpl-fetch-unl)
      - richard/xrpl-peermon <sup>c++</sup>[🧱](https://github.com/RichardAH/xrpl-peermon) <sub>*A peer monitor for the XRPL*</sub>
      - richard/validator-keys-from-dice <sup>js</sup>[🧱](https://github.com/RichardAH/validator-keys-from-dice)
      - richard/validator-keys-tool-portable-binary [🧱](https://github.com/RichardAH/validator-keys-tool-portable-binary)
      - richard/validator-keys-tool [🧱](https://github.com/RichardAH/validator-keys-tool)
      - richard/xrpl-validation-collector [🧱](https://github.com/RichardAH/xrpl-validation-collector)
    - []()
    - **Ripple**
      - ripple/tx-reporter [🧱](https://github.com/ripple/tx-reporter)
      - ripple/validator-history-service <sup>js/ts</sup>[🧱](https://github.com/ripple/validator-history-service)
      - ripple/validator-keys-tool <sup>c++</sup>[🧱](https://github.com/ripple/validator-keys-tool) <sub>*Generate master and ephemeral rippled validator keys*</sub>
      - ripple/validator-domain-verifier <sup>js</sup>[🧱](https://github.com/ripple/validator-domain-verifier)
      - ripple/rippledmon [🧱](https://github.com/ripple/rippledmon)
      - ripple/ripple-libpp <sup>c++</sup>[🧱](https://github.com/ripple/ripple-libpp) <sub>*Standalone RCL-compatible transaction signing and serialization library*</sub>
    - []()
    - **D.Schwartz**
      - JoelKatz/getLedger <sup>c++ json</sup>[🧱](https://github.com/JoelKatz/getLedger) <sub>*Retrieve an XRP Ledger in JSON by sequence number*</sub>
    - []()
    - **dangell7/Transia-RnD** [🧱](https://github.com/dangell7) [🧱](https://github.com/Transia-RnD)
      - Transia-RnD/xrpld-publisher <sup>py ts</sup>[🧱](https://github.com/Transia-RnD/xrpld-publisher) <sub>*Library that provides functionality for managing and publishing XRPL validator lists (VLs). It includes a client for interacting with the XRPLD Publisher API and a client for managing validator keys and generating VL manifests*</sub>
    - []()
  - **More Ledger Tools**
    - **Nixer89/xrpl.services**
      - nixer89/ledger-observer <sup>clojure</sup>[🧱](https://github.com/nixer89/ledger-observer) [🌎](https://xrpldata.com/) <sub>*real-time visualization of the XRP Ledger*</sub>
      - nixer89/xrpl-data-api <sup>ts</sup>[🧱](https://github.com/nixer89/xrpl-data-api) <sub>*api to provide xrp ledger data*</sub>
    - []()
    - **JScottBranson** [🧱](https://github.com/jscottbranson/) [🌎](https://cabbit.tech/) [🌎](https://rabbitkick.club) [🐦](https://twitter.com/jscottbranson)
      - jscottbranson/xrpl-validation-tracker [🧱](https://github.com/jscottbranson/xrpl-validation-tracker) <sub>*Aggregate, store, and parse XRP Ledger validation stream data*</sub>
      - jscottbranson/rippled-livenet-monitor [🧱](https://github.com/jscottbranson/rippled-livenet-monitor)
      - jscottbranson/rippled-examples [🧱](https://github.com/jscottbranson/rippled-examples)
      - jscottbranson/xrpl_unl_parser [🧱](https://github.com/jscottbranson/xrpl_unl_parser)
      - jscottbranson/XRPL-UNL-Domain-Tool [🧱](https://github.com/jscottbranson/XRPL-UNL-Domain-Tool)
      - jscottbranson/server_configs [🧱](https://github.com/jscottbranson/server_configs)
      - jscottbranson/xrpl-validation-tracker [🧱](https://github.com/jscottbranson/xrpl-validation-tracker)
    - []()
    - gregtatcam/xrpl-peermon <sup>c</sup>[🧱](https://github.com/gregtatcam/xrpl-peermon)
    - gregtatcam/xrpl-peersmon <sup>c++</sup>[🧱](https://github.com/gregtatcam/xrpl-peersmon)
    - XRPLWin/ [🧱](https://github.com/XRPLWin) [🧱](https://github.com/zgrguric) [🌎](https://xrpl.win/) <sub>*several php tools*</sub>
      - XRPLWin/XWA <sup>php js 🚧</sup>[🧱](https://github.com/XRPLWin/XWA) <sub>*XRP Ledger Analyzer*</sub>
    - mvadari/xrpl-node-detective [🧱](https://github.com/mvadari/xrpl-node-detective)
    - elmurci/xrpl-node-manager <sup>rust js 🚧</sup>[🧱](https://github.com/elmurci/xrpl-node-manager)
    - david-osl/xrp cluster monitoring [🌎](https://david-osl.github.io/xrp_cluster_monitoring/) [🧱](https://github.com/david-osl/xrp_cluster_monitoring)
    - antIggl/xrpl-unl-manager <sup>py</sup>[🧱](https://github.com/antIggl/xrpl-unl-manager)
    - mtouloup/xrpl-unl-decoder <sup>py</sup>[🧱](https://github.com/mtouloup/xrpl-unl-decoder)
  - []()



<br><br>








<br><br>

## 
##### <sup>*TOC*</sup> [🏠](/README.md) [🐞](/index/legend.md) <sup>*1.1 Overview*</sup>[👇](/xrpl/AWESOME-XRPL.md) <sup>*1.2 Rippled*</sup>✋🏿 <sup>*1.3 cryptography*</sup>[👇](/xrpl/AWESOME-XRPL-CRYPTOGRAPHY.md) <sup>*1.4 client*</sup>[👇](/xrpl/AWESOME-XRPL-SOFTWARE.md) <sup>*1.5 ecosystem*</sup>[👇](/xrpl/AWESOME-XRPL-ECOSYSTEM.md) <sup>*1.6 web3*</sup>[👇](/xrpl/AWESOME-XRPL-WEB3.md) <sup>*1.7 sidechains*</sup>[👇](/xrpl/AWESOME-XRPL-SIDE.md)




[![SVG Banners](https://svg-banners.vercel.app/api?type=glitch&text1=🕳🤹&width=800&height=60)](https://github.com/Akshay090/svg-banners)









