# Stock image manifest — OnePlus 11 CPH2447, build CPH2447_16.0.5.1301

Every file was extracted from the official CPH2447_16.0.5.1301 `payload.bin` with per-operation SHA-256 checks and a final partition SHA-256 verified against the OTA manifest. Verify a downloaded file with `sha256sum <file>` before flashing. Note: `my_product.img` and `my_stock.img` are stored in the repo as `.part1`/`.part2` splits (GitHub's 2 GiB per-object limit); the hashes below are for the rejoined files.

| Partition | File | Size (bytes) | SHA-256 |
|---|---|---|---|
| abl | abl.img | 270336 | 7cbdf8ea51672017ccd33d50aafded88f6f2e546b4aabc0cf447e730986249b9 |
| aop | aop.img | 282624 | 6b253b8ef3f1c739e9894fd61a884ba008c02f27b89753c66f14bd0433ea9271 |
| aop_config | aop_config.img | 16384 | 25d9ea6359b486ddf5eeb3c2b5aa6b99761db24c9ca9ab8da869ad73b5c0cf1a |
| bluetooth | bluetooth.img | 1224704 | 2fb35ca7f7bfd699d2924c4c7d86efc439c870d1be79f60d0142099f9ff7e064 |
| boot | boot.img | 201326592 | a159e99de2655b4f8e72cc4c313dac2e15559d37eef42b60f048995349f1c795 |
| cpucp | cpucp.img | 192512 | c2d534746d18f8e880cf1c0f9cc35ce318f7234544960ee6d74d3062f743dcd0 |
| devcfg | devcfg.img | 57344 | ae7417ddae58ac17807e7ca1b489fa15d517ce47c77b251bf3026beee5196186 |
| dsp | dsp.img | 67108864 | 3374d8e12692d6f40f699591cb01002e26d96959cadd611fb6b0f9a88e4e65c4 |
| dtbo | dtbo.img | 25165824 | 5eb302c385fae944568e9dec82e0bf75ccb76a1e4b89398cf8210571579ea99f |
| engineering_cdt | engineering_cdt.img | 1048576 | eb185f7ef73f848944379c4b6b909bf21ef5a3230585247769736b55017bc7f2 |
| featenabler | featenabler.img | 98304 | 64388dc7e020ec15508277c69e213a4e4b67d075aad1cd7d0ff48a5d62404508 |
| hyp | hyp.img | 1654784 | ad6742b973a674c0e5fb454653ef2296d056fbb64a464c0eecf675392c75608c |
| imagefv | imagefv.img | 77824 | 772f821ecaedd9f4b7789314271668ef76e041286d22f8ae9e5a22dc44c4d9e7 |
| init_boot | init_boot.img | 8388608 | d50af3dae16874734db9396b342c2d9be12ea705e2c29982c551608bbfd39671 |
| keymaster | keymaster.img | 413696 | 7b9f75ab1b6460f6adc91295163c21866016bb140a0bc76a8fb5f35c25d46d8d |
| modem | modem.img | 310325248 | d6d71eaa7d151523f72caddf82e407616b1d072807a93984f49c7d42a7e16b27 |
| my_bigball | my_bigball.img | 335872 | 41ee31050d769c20c4c77e31549d9c7f978170e1a5a60fe92bdcbd5ff5cb5000 |
| my_carrier | my_carrier.img | 335872 | 0ec6d42a76b72519bd0df67a41595cb7faafd34bedc754cc74bcb0a805d09905 |
| my_engineering | my_engineering.img | 335872 | 5ef6bcc1f0f91a0a5d0125199705ab210045ccf7452d13ca95915045787aa875 |
| my_heytap | my_heytap.img | 335872 | 613d09688b0447ef6f0c4ebf07bf169708af5cbfabb65ba7fb29fbaee1a682ca |
| my_manifest | my_manifest.img | 516096 | a3cd01389e118edff27cff82d979903378f57486d85391ffb4f3efdcdbf284dd |
| my_product | my_product.img | 2897543168 | e539d3bc4b98476a1b65aa8d79a8c550436d88f65db1681c767b1dbc2b4c4450 |
| my_region | my_region.img | 3166208 | f857b1bccf7ef9fbf9f022e3663f73989134c0855592958383efad974a770a70 |
| my_stock | my_stock.img | 3079491584 | bd6c5c818714caee3cced853942f6eb6276886264fddecd6a25622961a0af171 |
| odm | odm.img | 1511489536 | 114e84f58a2185374b7e16322a08207b1ac1b6e570b9f5d352dd2d465cb76fce |
| oplus_sec | oplus_sec.img | 851968 | 3464afad9f12eba57088207497358f630755e5b77a7dd67111a7edcb028e2631 |
| oplusstanvbk | oplusstanvbk.img | 2236416 | 41ec34a135ef0ab396844906044b0ed491f6f7854b7aa6a91efd461945e9350a |
| product | product.img | 9383936 | 3ffac9ac2c0089fcb11e1029ffa06674e98674d2af46111392a17b78c18abdae |
| qupfw | qupfw.img | 57344 | 4a82ca0b3973ecaa5366378e693470d0f9c4e466df28bf8d33b84ae557e804c8 |
| recovery | recovery.img | 104857600 | 526f79aee311f21d1cf3156cbd313f29012ca94d190d1e05ad30c9fe0c95ba50 |
| shrm | shrm.img | 65536 | 25c3a15c67e8d4117c68836ff0b4f5669de65c5e4ffebde8f951b12a98c9e20d |
| splash | splash.img | 331776 | 7113e1df901223ca69779fc49a30e23c275ec9913612f743a4fcc83ea3f667a7 |
| system | system.img | 925081600 | ef0ba6be6035275b7a70571e91890e3a63086618dff4ab1a4deb3d682e3fb244 |
| system_dlkm | system_dlkm.img | 425984 | fe452c196b0d40df6e68243f1586dcf0bcc0db189592a4dfa35bd408cb1acd09 |
| system_ext | system_ext.img | 934920192 | deade38131d9989fbdb614affc06f97e0e60fdcafa474fbb7dc454b471894b17 |
| tz | tz.img | 3973120 | a69afbdd4960f2022fa8b318b0ba23bcda28a8541e7b388dad2be201e126001a |
| uefi | uefi.img | 3153920 | 54d3b6af9375cff50c31bd61220104f25ad9050dc0d6c171e0c8c4fda464d055 |
| uefisecapp | uefisecapp.img | 180224 | 560a7c171d25215531c914d9a5004349dd12d506b28cd1777ebe598c8c85f28c |
| vbmeta | vbmeta.img | 12288 | cbced8bf2ee6c7ba743e6364b23408427b8e589f248ea00c93c24276736be9df |
| vbmeta_system | vbmeta_system.img | 8192 | aaa7c452a8525e4b0e5dce348f99882ef8aae495863a2397415e4d9932d23e25 |
| vbmeta_vendor | vbmeta_vendor.img | 4096 | 4443233ef8277108821a984da633ca768caef82568ee54b23f0863b00a2b2f07 |
| vendor | vendor.img | 710836224 | a17f1ea50091166f6124b2d2e5915a7854ead31b165d880d4797d0768a0ac857 |
| vendor_boot | vendor_boot.img | 201326592 | 592640572fa35999d95f0d0800c4dce305d6053a9ec0bc682bea6ab773341af5 |
| vendor_dlkm | vendor_dlkm.img | 173043712 | 1df4b07c3949094af9594827a929ee6b0ac8484f9c9ca2573d4d6707e1fc7d14 |
| xbl | xbl.img | 1208320 | f1342f19bafcb263c0ade43e6e7162c9fdfc768c8aae065b1e83dd31fcbf5ea2 |
| xbl_config | xbl_config.img | 192512 | fe8348ba83d6cb11724e12859cd7120e1c473268a10f06691e77fbd582335283 |
| xbl_ramdump | xbl_ramdump.img | 872448 | be69c5cb7cf91685e7e890063e6eccce9997f90f5fce8f18851a942e22eb2399 |
