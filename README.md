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
      <p>My first project will be a super silent (I hope) mechanical keyboard <a href="https://github.com">PhantomBoard</a> powered by Vertex Mk4.4. (On hiatus for now)</p>
      <p> ⚡Powered by STM32F405RGT6 QF64 and the PCB dimensions are 📏24.2*40.6mm (width*height), roughly the size of an adult's thumb 👍</p>
      <p><strong><ins>🚨Note🚨:</ins></strong> I prefer assembling myself so all the PCBs I make <strong><ins>🔴REQUIRE YOU TO SOLDER COMPONENTS YOURSELF🔴</ins></strong>.</p>
      <p>So far, Vertex Mk4.4 is my first and only dev board. More coming soon🙌! (Depends on whether I need different MCUs for future projects.)</p>

## Capabilities
### Microcontroller
- **STM32F405RGT6** (ARM Cortex-M4, up to 168MHz, LQFP64)
- USB Full-Speed 2.0 with onboard ESD protection
- SWD debug header (TC2030-SWD compatible) for programming/debugging
- Reset and bootloader-entry buttons
### Expansion
- 42 GPIO and 14 PWM-capable pins (refer to schematic below & STM32F405RGT6-QF64 datasheet)
- 3 independent I2C buses free for additional sensors/peripherals
- 3 SPI and 2 UART interfaces 

## Vertex Mk4.4 PCB
### Schematic
<img width="1130" height="663" alt="Screenshot_7-8-2026_23911_" src="https://github.com/user-attachments/assets/4802f946-ac55-4b51-934c-954beac423d1" />

## BOM

<table style="border-collapse: collapse; width: 100%; font-family: Arial, sans-serif; font-size: 14px">
  <thead>
    <tr>
      <th style="background-color: #f1f5f9; color: #1e293b; text-align: left; padding: 8px; font-weight: bold; border: 1px solid #e2e8f0">Item</th>
      <th style="background-color: #f1f5f9; color: #1e293b; text-align: left; padding: 8px; font-weight: bold; border: 1px solid #e2e8f0">Parts</th>
      <th style="background-color: #f1f5f9; color: #1e293b; text-align: left; padding: 8px; font-weight: bold; border: 1px solid #e2e8f0">Qty.</th>
      <th style="background-color: #f1f5f9; color: #1e293b; text-align: left; padding: 8px; font-weight: bold; border: 1px solid #e2e8f0">Unit price(USD)</th>
      <th style="background-color: #f1f5f9; color: #1e293b; text-align: left; padding: 8px; font-weight: bold; border: 1px solid #e2e8f0">Price per lot(USD)</th>
      <th style="background-color: #f1f5f9; color: #1e293b; text-align: left; padding: 8px; font-weight: bold; border: 1px solid #e2e8f0">Source</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">33pF 0402</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0195</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.95</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005002960548572.html?spm=a2g0o.productlist.main.1.2724aRjtaRjtjg&amp;algo_pvid=273f926f-5b51-4a0c-b6ff-941ef61254cd&amp;pdp_ext_f=%7B%22order%22%3A%22144%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005002960548572%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">10nF 1206</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0314</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">3.14</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005007176206143.html?spm=a2g0o.productlist.main.1.75244Dz04Dz0a2&amp;algo_pvid=e20f9481-cc4c-46ed-a6e1-b2569239c797&amp;pdp_ext_f=%7B%22order%22%3A%22357%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007176206143%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">100nF 0402</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">7</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0422</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">4.22</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005012522149817.html?spm=a2g0o.productlist.main.6.20b943faUZYMT2&amp;algo_pvid=62e96aec-8ae0-41c5-99bc-5a51672693a2&amp;pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012522149817%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1uF 0603</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0484</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2.42</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005007160988407.html?spm=a2g0o.productlist.main.4.2dad66d30HNdsF&amp;aem_p4p_detail=202608061846053641279657893500000031748&amp;algo_pvid=6cfb904c-a425-475c-8bcd-6b7a12159c50&amp;pdp_ext_f=%7B%22order%22%3A%221522%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007160988407%7C_p_origin_prod%3A&amp;search_p4p_id=202608061846053641279657893500000031748_1</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2.2uF 0603</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0672</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">3.36</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005007160988407.html?spm=a2g0o.productlist.main.4.2dad66d30HNdsF&amp;aem_p4p_detail=202608061846053641279657893500000031748&amp;algo_pvid=6cfb904c-a425-475c-8bcd-6b7a12159c50&amp;pdp_ext_f=%7B%22order%22%3A%221522%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007160988407%7C_p_origin_prod%3A&amp;search_p4p_id=202608061846053641279657893500000031748_1</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">4.7uF 0402</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0942</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">4.71</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005012364450156.html?spm=a2g0o.productlist.main.2.4873bme3bme3KF&amp;algo_pvid=b7cbaa29-1396-4ee3-b782-cc734cfed9f9&amp;pdp_ext_f=%7B%22order%22%3A%22630%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012364450156%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">10uF 0805</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0832</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">4.16</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005008523091680.html?spm=a2g0o.productlist.main.4.4364101apUC04J&amp;aem_p4p_detail=202608061858424677997433533380000034497&amp;algo_pvid=b67651cf-bfca-4baa-ad24-9fc2c1249cca&amp;pdp_ext_f=%7B%22order%22%3A%22944%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008523091680%7C_p_origin_prod%3A&amp;search_p4p_id=202608061858424677997433533380000034497_1</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic capacitor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">22uF 0805</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0988</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">4.94</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005008523091680.html?spm=a2g0o.productlist.main.4.4364101apUC04J&amp;aem_p4p_detail=202608061858424677997433533380000034497&amp;algo_pvid=b67651cf-bfca-4baa-ad24-9fc2c1249cca&amp;pdp_ext_f=%7B%22order%22%3A%22944%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008523091680%7C_p_origin_prod%3A&amp;search_p4p_id=202608061858424677997433533380000034497_1</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ferrite bead SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0"> 50mΩ 120Ω@100MHz 2A 0603</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0116</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.16</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005012116787152.html?spm=a2g0o.productlist.main.4.263816ea7rpi5g&amp;aem_p4p_detail=2026080619005087495149417070000032270&amp;algo_pvid=b2e3591e-925c-4f0e-81bf-e5384869aa58&amp;pdp_ext_f=%7B%22order%22%3A%2235%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012116787152%7C_p_origin_prod%3A&amp;search_p4p_id=2026080619005087495149417070000032270_1</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">USB C receptacle</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">GCT_USB4085</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.252</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">6.26</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005010442732661.html?spm=a2g0o.productlist.main.5.5a45mTb8mTb8gC&amp;algo_pvid=eb26e3f2-1a74-460f-a117-79aa428dcdc0&amp;pdp_ext_f=%7B%22order%22%3A%225%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010442732661%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">THT male connector</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">4(1x2)|1(1x16)|1(1x22)|1(1x5) P1.00mm</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">-</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.28</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2.56</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005006790453916.html?spm=a2g0o.productlist.main.1.686f588d3F6LGa&amp;algo_pvid=5cb65832-0523-4dea-a32b-3d35ab20cc37&amp;pdp_ext_f=%7B%22order%22%3A%2246%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005006790453916%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic resistor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">5k1 0402</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0118</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.18</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005005982446651.html?spm=a2g0o.productlist.main.1.499ero3Vro3V4h&amp;algo_pvid=0e3539f1-deb6-41ea-8dc5-1258ce9e257a&amp;pdp_ext_f=%7B%22order%22%3A%22472%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005982446651%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic resistor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">10k 0402</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0114</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.14</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005005982446651.html?spm=a2g0o.productlist.main.1.499ero3Vro3V4h&amp;algo_pvid=0e3539f1-deb6-41ea-8dc5-1258ce9e257a&amp;pdp_ext_f=%7B%22order%22%3A%22472%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005005982446651%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Ceramic resistor SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1M 0603</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0148</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.48</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005010109041806.html?spm=a2g0o.productlist.main.1.4a12d8mrd8mrat&amp;algo_pvid=af229fc5-fa32-4342-b395-68c0d5cc9c78&amp;pdp_ext_f=%7B%22order%22%3A%22328%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005010109041806%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Push button SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">SW_SPST_B3U-1000P</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">2</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.0146</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1.46</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005009548875400.html?spm=a2g0o.productlist.main.1.56ebP1y3P1y3Yd&amp;algo_pvid=e205a10a-479c-4a7d-81eb-9951e2930e82&amp;pdp_ext_f=%7B%22order%22%3A%223%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005009548875400%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Unidirectional ESD SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">USBLC6-2SC6</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.313</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">3.13</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005007348100430.html?spm=a2g0o.productlist.main.1.266415aaYuX2ik&amp;algo_pvid=d3961607-acf5-4734-90d5-cba57721460d&amp;pdp_ext_f=%7B%22order%22%3A%22385%22%2C%22spu_best_type%22%3A%22price%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005007348100430%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Low-dropout linear voltage regulator SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">AMS1117-3.3</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.068</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.68</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005008607449037.html?spm=a2g0o.productlist.main.1.64233f4bmJKS9m&amp;algo_pvid=8a23942f-891e-444d-bb7f-997bb1af465c&amp;pdp_ext_f=%7B%22order%22%3A%221277%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005008607449037%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">MCU</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">STM32F405RGT6</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">3.15</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">3.15</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/4000117720745.html?spm=a2g0o.productlist.main.4.4c034999OY8gaV&amp;aem_p4p_detail=202608061954067234269471428120000053854&amp;algo_pvid=9696ab0c-0194-4262-80f6-0d6907be18ba&amp;pdp_ext_f=%7B%22order%22%3A%22917%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A4000117720745%7C_p_origin_prod%3A&amp;search_p4p_id=202608061954067234269471428120000053854_1</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Crystal oscillator SMD</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">X322512MSB4SI</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">1</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.21</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">0.21</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">https://www.aliexpress.com/item/1005012668862128.html?spm=a2g0o.productlist.main.3.da16pbzFpbzFcs&amp;algo_pvid=96cc8d8e-f6af-4891-bf81-69791a5fffa3&amp;pdp_ext_f=%7B%22order%22%3A%22-1%22%2C%22eval%22%3A%221%22%2C%22fromPage%22%3A%22search%22%7D&amp;utparam-url=scene%3Asearch%7Cquery_from%3A%7Cx_object_id%3A1005012668862128%7C_p_origin_prod%3A</td>
    </tr>
    <tr>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">Total+Shipping+Tax</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">-</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">-</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">-</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">64.57±</td>
      <td style="color: #334155; text-align: left; padding: 8px; border: 1px solid #e2e8f0">-</td>
    </tr>
  </tbody>
</table>



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
