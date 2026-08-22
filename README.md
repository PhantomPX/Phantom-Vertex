# Phantom-Vertex

<h2>Vertex Mk4.4 Dev Board</h2>

<p align="center">
  <a href="https://github.com/user-attachments/assets/54ca32f1-3a24-44c7-9a8a-99f23128513a">
    <img
      src="https://github.com/user-attachments/assets/54ca32f1-3a24-44c7-9a8a-99f23128513a"
      alt="PhantomPX Vertex Mk4.4 Pins"
      width="700"
    />
  </a>
</p>
      <p>Journey of making my own dev board for studying and general purpose!</p>
      <p>I got interested in making my own electronics stuff. I'm on a quest to fill my room with cool and useful engineering machines. The first step to any great machine is the electronic components inside it. I'm very new to this, so I'm starting off simple.</p>
      <p>My first complete project will be a super silent (I hope) mechanical keyboard <a href="https://github.com">PhantomBoard</a> powered by Vertex Mk4.4. (Still in progress.)</p>
      <p> ⚡Powered by STM32F405RGT6 QF64 and the PCB dimensions are 24.2*40.6mm (width*height), roughly the size of an adult's thumb 👍</p>
      <p><strong><ins>🚨Note🚨:</ins></strong> I prefer assembling myself so all the PCBs I make <strong><ins>🔴REQUIRE YOU TO SOLDER COMPONENTS YOURSELF🔴</ins></strong>.</p>
      <p>So far, Vertex Mk4.4 is my first and only dev board. More coming soon🙌! (Depends on whether I need different MCUs for future projects.)</p>

## Vertex Mk4.4 PCB
### Schematic
<img width="1130" height="663" alt="Screenshot_7-8-2026_23911_" src="https://github.com/user-attachments/assets/4802f946-ac55-4b51-934c-954beac423d1" />

| Item | Parts | Qty. | Price(USD) | Source |
| --- | --- | --- | --- | --- |
| Ceramic capacitor SMD | 33pF 0402 | 2 | 1.95 | https://www.aliexpress.com/item/1005002960548572.html?spm=a2g0o.productlist.main.1.2724aRjtaRjtjg&algo_pvid=273f926f-5b51-4a0c-b6ff-941ef61254cd&pdp_ext_f=%7B%22order%22%3A%22144%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005002960548572%7C_p_origin_prod%3A |
| Ceramic capacitor SMD | 10nF 1206 | 1 | 3.14 | https://www.aliexpress.com/item/1005007176206143.html?spm=a2g0o.productlist.main.1.75244Dz04Dz0a2&algo_pvid=e20f9481-cc4c-46ed-a6e1-b2569239c797&pdp_ext_f=%7B%22order%22%3A%22357%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007176206143%7C_p_origin_prod%3A |
| Ceramic capacitor SMD | 100nF 0402 | 7 | 4.22 | https://www.aliexpress.com/item/1005012522149817.html?spm=a2g0o.productlist.main.6.20b943faUZYMT2&algo_pvid=62e96aec-8ae0-41c5-99bc-5a51672693a2&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012522149817%7C_p_origin_prod%3A |
| Ceramic capacitor SMD | 1uF 0603 | 1 | 2.42 | https://www.aliexpress.com/item/1005007160988407.html?spm=a2g0o.productlist.main.4.2dad66d30HNdsF&aem_p4p_detail=202608061846053641279657893500000031748&algo_pvid=6cfb904c-a425-475c-8bcd-6b7a12159c50&pdp_ext_f=%7B%22order%22%3A%221522%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007160988407%7C_p_origin_prod%3A&search_p4p_id=202608061846053641279657893500000031748_1 |
| Ceramic capacitor SMD | 2.2uF 0603 | 2 | 3.36 | https://www.aliexpress.com/item/1005007160988407.html?spm=a2g0o.productlist.main.4.2dad66d30HNdsF&aem_p4p_detail=202608061846053641279657893500000031748&algo_pvid=6cfb904c-a425-475c-8bcd-6b7a12159c50&pdp_ext_f=%7B%22order%22%3A%221522%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007160988407%7C_p_origin_prod%3A&search_p4p_id=202608061846053641279657893500000031748_1 |
| Ceramic capacitor SMD | 4.7uF 0402 | 1 | 4.71 | https://www.aliexpress.com/item/1005012364450156.html?spm=a2g0o.productlist.main.2.4873bme3bme3KF&algo_pvid=b7cbaa29-1396-4ee3-b782-cc734cfed9f9&pdp_ext_f=%7B%22order%22%3A%22630%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012364450156%7C_p_origin_prod%3A |
| Ceramic capacitor SMD | 10uF 0805 | 1 | 4.16 | https://www.aliexpress.com/item/1005008523091680.html?spm=a2g0o.productlist.main.4.4364101apUC04J&aem_p4p_detail=202608061858424677997433533380000034497&algo_pvid=b67651cf-bfca-4baa-ad24-9fc2c1249cca&pdp_ext_f=%7B%22order%22%3A%22944%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008523091680%7C_p_origin_prod%3A&search_p4p_id=202608061858424677997433533380000034497_1 |
| Ceramic capacitor SMD | 22uF 0805 | 1 | 4.94 | https://www.aliexpress.com/item/1005008523091680.html?spm=a2g0o.productlist.main.4.4364101apUC04J&aem_p4p_detail=202608061858424677997433533380000034497&algo_pvid=b67651cf-bfca-4baa-ad24-9fc2c1249cca&pdp_ext_f=%7B%22order%22%3A%22944%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008523091680%7C_p_origin_prod%3A&search_p4p_id=202608061858424677997433533380000034497_1 |
| Ferrite bead SMD | 50mΩ 120Ω@100MHz 2A 0603 | 1 | 1.16 | https://www.aliexpress.com/item/1005012116787152.html?spm=a2g0o.productlist.main.4.263816ea7rpi5g&aem_p4p_detail=2026080619005087495149417070000032270&algo_pvid=b2e3591e-925c-4f0e-81bf-e5384869aa58&pdp_ext_f=%7B%22order%22%3A%2235%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012116787152%7C_p_origin_prod%3A&search_p4p_id=2026080619005087495149417070000032270_1 |
| USB C receptacle | GCT_USB4085 | 1 | 6.26 | https://www.aliexpress.com/item/1005010442732661.html?spm=a2g0o.productlist.main.5.5a45mTb8mTb8gC&algo_pvid=eb26e3f2-1a74-460f-a117-79aa428dcdc0&pdp_ext_f=%7B%22order%22%3A%225%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010442732661%7C_p_origin_prod%3A |
| THT connector | 4(1x2)\|1(1x16)\|1(1x22)\|1(1x5) P1.00mm | - | 2.56 | https://www.aliexpress.com/item/1005006790453916.html?spm=a2g0o.productlist.main.1.686f588d3F6LGa&algo_pvid=5cb65832-0523-4dea-a32b-3d35ab20cc37&pdp_ext_f=%7B%22order%22%3A%2246%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006790453916%7C_p_origin_prod%3A |
| Ceramic resistor SMD | 5k1 0402 | 2 | 1.18 | https://www.aliexpress.com/item/1005005982446651.html?spm=a2g0o.productlist.main.1.499ero3Vro3V4h&algo_pvid=0e3539f1-deb6-41ea-8dc5-1258ce9e257a&pdp_ext_f=%7B%22order%22%3A%22472%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005982446651%7C_p_origin_prod%3A |
| Ceramic resistor SMD | 10k 0402 | 2 | 1.14 | https://www.aliexpress.com/item/1005005982446651.html?spm=a2g0o.productlist.main.1.499ero3Vro3V4h&algo_pvid=0e3539f1-deb6-41ea-8dc5-1258ce9e257a&pdp_ext_f=%7B%22order%22%3A%22472%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005982446651%7C_p_origin_prod%3A |
| Ceramic resistor SMD | 1M 0603 | 1 | 1.48 | https://www.aliexpress.com/item/1005010109041806.html?spm=a2g0o.productlist.main.1.4a12d8mrd8mrat&algo_pvid=af229fc5-fa32-4342-b395-68c0d5cc9c78&pdp_ext_f=%7B%22order%22%3A%22328%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010109041806%7C_p_origin_prod%3A |
| Push button SMD | SW_SPST_B3U-1000P | 2 | 1.46 | https://www.aliexpress.com/item/1005009548875400.html?spm=a2g0o.productlist.main.1.56ebP1y3P1y3Yd&algo_pvid=e205a10a-479c-4a7d-81eb-9951e2930e82&pdp_ext_f=%7B%22order%22%3A%223%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009548875400%7C_p_origin_prod%3A |
| Unidirectional ESD SMD | USBLC6-2SC6 | 1 | 3.13 | https://www.aliexpress.com/item/1005007348100430.html?spm=a2g0o.productlist.main.1.266415aaYuX2ik&algo_pvid=d3961607-acf5-4734-90d5-cba57721460d&pdp_ext_f=%7B%22order%22%3A%22385%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007348100430%7C_p_origin_prod%3A |
| Low-dropout linear voltage regulator SMD | AMS1117-3.3 | 1 | 0.68 | https://www.aliexpress.com/item/1005008607449037.html?spm=a2g0o.productlist.main.1.64233f4bmJKS9m&algo_pvid=8a23942f-891e-444d-bb7f-997bb1af465c&pdp_ext_f=%7B%22order%22%3A%221277%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008607449037%7C_p_origin_prod%3A |
| MCU | STM32F405RGT6 | 1 | 3.15 | https://www.aliexpress.com/item/4000117720745.html?spm=a2g0o.productlist.main.4.4c034999OY8gaV&aem_p4p_detail=202608061954067234269471428120000053854&algo_pvid=9696ab0c-0194-4262-80f6-0d6907be18ba&pdp_ext_f=%7B%22order%22%3A%22917%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000117720745%7C_p_origin_prod%3A&search_p4p_id=202608061954067234269471428120000053854_1 |
| Crystal oscillator SMD | X322512MSB4SI | 1 | 0.21 | https://www.aliexpress.com/item/1005012668862128.html?spm=a2g0o.productlist.main.3.da16pbzFpbzFcs&algo_pvid=96cc8d8e-f6af-4891-bf81-69791a5fffa3&pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012668862128%7C_p_origin_prod%3A |
| Total | - | - | 51.31± | - |


### Footprint
<table>
  <tr>
    <td>
      <img width="223" height="365" alt="vertex mk4 4 ftpt f" src="https://github.com/user-attachments/assets/b2fd1b0e-a7bb-4718-8832-8a79aa41cbac" />
    </td>
    <td>
      <img width="223" height="365" alt="vertex mk4 4 ftpt b" src="https://github.com/user-attachments/assets/80290423-7b01-43dc-b905-6d0840373d49" />
    </td>
  </tr>
  <tr>
    <td>
     <img width="223" height="365" alt="image" src="https://github.com/user-attachments/assets/89c87054-2a60-4ec8-9514-4bb022bf83f0" />
    </td>
    <td>
      <img width="223" height="365" alt="Screenshot 2026-08-07 021950" src="https://github.com/user-attachments/assets/f7ce62b7-7a9d-4492-aefd-d4d19efbb56c" />
    </td>
  </tr>
</table>



### 3D View
<table>
  <tr>
    <td>
      <img width="400" height="400" alt="vertex mk4 Top" src="https://github.com/user-attachments/assets/ee6b7511-3072-43ea-a687-0719a4e3fd2a" />
    </td>
    <td>
      <img width="400" height="400" alt="vertex mk4 Bottom" src="https://github.com/user-attachments/assets/ee41a024-3188-416b-99f3-673b66a65500" />
    </td>
  </tr>
  <tr>
    <td>
      <img width="400" height="400" alt="vertex mk4 Side3" src="https://github.com/user-attachments/assets/e53d7afb-ec61-4b05-bfc2-92e3fa88290a" />
    </td>
    <td>
      <img width="400" height="400" alt="vertex mk4 Side4" src="https://github.com/user-attachments/assets/6d8a47f2-9354-47ac-a17b-55f2d285b97d" />
    </td>
  </tr>
</table>

## Check out my other stuff
[HERE](https://github.com/PhantomPX/Phantom-Dev-Boards)
