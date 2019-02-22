# Hybrid

>Developer Guideline

## Variables

### Layer z-index

|       Layer        | z-index |          comment          |
|:------------------:|:-------:|:-------------------------:|
|       Normal       |   100   |        Basic layer        |
|        Hold        |   150   |      Held components      |
|       Fixed        |   200   |       Fixed z-index       |
| Interface-backdrop |   350   | Backdrop of the interface |
|     Interface      |   400   |      Interface layer      |
|       Sticky       |   500   |     Sticky components     |
|   Modal-backdrop   |   550   |   Backdrop of the modal   |
|       Modal        |   600   |        Modal layer        |

### Grid break points

|      | Phone | Tablet | Tablet-Pro | Laptop | Desktop-FHD | Desktop-WQHD |
|:----:|:-----:|:------:|:----------:|:------:|:-----------:|:------------:|
|  0   |   *   |        |            |        |             |              |
| 767  |   *   |   *    |            |        |             |              |
| 1023 |       |   *    |     *      |        |             |              |
| 1365 |       |        |     *      |   *    |             |              |
| 1919 |       |        |            |   *    |      *      |              |
| 2559 |       |        |            |        |      *      |      *       |
|  ∞   |       |        |            |        |             |      *       |

### Font unicode range

| Language | unicode rage |
|:--------:|:------------:|
|  en_US   |              |
|   CJK    |              |

### Color Palette

<table>
    <tr>
        <th></th>
        <th>50</th>
        <th>100</th>
        <th>200</th>
        <th>300</th>
        <th>400</th>
        <th>500</th>
        <th>600</th>
        <th>700</th>
        <th>800</th>
        <th>900</th>
        <th>A100</th>
        <th>A200</th>
        <th>A400</th>
        <th>A700</th>
    </tr>
    <tr>
        <td>Red</td>
        <td bgcolor="#FFEBEE">#FFEBEE</td>
        <td bgcolor="#FFCDD2">#FFCDD2</td>
        <td bgcolor="#EF9A9A">#EF9A9A</td>
        <td bgcolor="#E57373">#E57373</td>
        <td bgcolor="#EF5350">#EF5350</td>
        <td bgcolor="#F44336">#F44336</td>
        <td bgcolor="#E53935">#E53935</td>
        <td bgcolor="#D32F2F">#D32F2F</td>
        <td bgcolor="#C62828">#C62828</td>
        <td bgcolor="#B71C1C">#B71C1C</td>
        <td bgcolor="#FF8A80">#FF8A80</td>
        <td bgcolor="#FF5252">#FF5252</td>
        <td bgcolor="#FF1744">#FF1744</td>
        <td bgcolor="#D50000">#D50000</td>
    </tr>
    <tr>
        <td>Pink</td>
        <td bgcolor="#FCE4EC">#FCE4EC</td>
        <td bgcolor="#F8BBD0">#F8BBD0</td>
        <td bgcolor="#F48FB1">#F48FB1</td>
        <td bgcolor="#F06292">#F06292</td>
        <td bgcolor="#EC407A">#EC407A</td>
        <td bgcolor="#E91E63">#E91E63</td>
        <td bgcolor="#D81B60">#D81B60</td>
        <td bgcolor="#C2185B">#C2185B</td>
        <td bgcolor="#AD1457">#AD1457</td>
        <td bgcolor="#880E4F">#880E4F</td>
        <td bgcolor="#FF80AB">#FF80AB</td>
        <td bgcolor="#FF4081">#FF4081</td>
        <td bgcolor="#F50057">#F50057</td>
        <td bgcolor="#C51162">#C51162</td>
    </tr>
    <tr>
        <td>Purple</td>
        <td bgcolor="#F3E5F5">#F3E5F5</td>
        <td bgcolor="#E1BEE7">#E1BEE7</td>
        <td bgcolor="#CE93D8">#CE93D8</td>
        <td bgcolor="#BA68C8">#BA68C8</td>
        <td bgcolor="#AB47BC">#AB47BC</td>
        <td bgcolor="#9C27B0">#9C27B0</td>
        <td bgcolor="#8E24AA">#8E24AA</td>
        <td bgcolor="#7B1FA2">#7B1FA2</td>
        <td bgcolor="#6A1B9A">#6A1B9A</td>
        <td bgcolor="#4A148C">#4A148C</td>
        <td bgcolor="#EA80FC">#EA80FC</td>
        <td bgcolor="#E040FB">#E040FB</td>
        <td bgcolor="#D500F9">#D500F9</td>
        <td bgcolor="#AA00FF">#AA00FF</td>
    </tr>
    <tr>
        <td>Deep_Purple</td>
        <td bgcolor="#EDE7F6">#EDE7F6</td>
        <td bgcolor="#D1C4E9">#D1C4E9</td>
        <td bgcolor="#B39DDB">#B39DDB</td>
        <td bgcolor="#9575CD">#9575CD</td>
        <td bgcolor="#7E57C2">#7E57C2</td>
        <td bgcolor="#673AB7">#673AB7</td>
        <td bgcolor="#5E35B1">#5E35B1</td>
        <td bgcolor="#512DA8">#512DA8</td>
        <td bgcolor="#4527A0">#4527A0</td>
        <td bgcolor="#311B92">#311B92</td>
        <td bgcolor="#B388FF">#B388FF</td>
        <td bgcolor="#7C4DFF">#7C4DFF</td>
        <td bgcolor="#651FFF">#651FFF</td>
        <td bgcolor="#6200EA">#6200EA</td>
    </tr>
    <tr>
        <td>Indigo</td>
        <td bgcolor="#E8EAF6">#E8EAF6</td>
        <td bgcolor="#C5CAE9">#C5CAE9</td>
        <td bgcolor="#9FA8DA">#9FA8DA</td>
        <td bgcolor="#7986CB">#7986CB</td>
        <td bgcolor="#5C6BC0">#5C6BC0</td>
        <td bgcolor="#3F51B5">#3F51B5</td>
        <td bgcolor="#3949AB">#3949AB</td>
        <td bgcolor="#303F9F">#303F9F</td>
        <td bgcolor="#283593">#283593</td>
        <td bgcolor="#1A237E">#1A237E</td>
        <td bgcolor="#8C9EFF">#8C9EFF</td>
        <td bgcolor="#536DFE">#536DFE</td>
        <td bgcolor="#3D5AFE">#3D5AFE</td>
        <td bgcolor="#304FFE">#304FFE</td>
    </tr>
    <tr>
        <td>Blue</td>
        <td bgcolor="#E3F2FD">#E3F2FD</td>
        <td bgcolor="#BBDEFB">#BBDEFB</td>
        <td bgcolor="#90CAF9">#90CAF9</td>
        <td bgcolor="#64B5F6">#64B5F6</td>
        <td bgcolor="#42A5F5">#42A5F5</td>
        <td bgcolor="#2196F3">#2196F3</td>
        <td bgcolor="#1E88E5">#1E88E5</td>
        <td bgcolor="#1976D2">#1976D2</td>
        <td bgcolor="#1565C0">#1565C0</td>
        <td bgcolor="#0D47A1">#0D47A1</td>
        <td bgcolor="#82B1FF">#82B1FF</td>
        <td bgcolor="#448AFF">#448AFF</td>
        <td bgcolor="#2979FF">#2979FF</td>
        <td bgcolor="#2962FF">#2962FF</td>
    </tr>
    <tr>
        <td>Light_Blue</td>
        <td bgcolor="#E1F5FE">#E1F5FE</td>
        <td bgcolor="#B3E5FC">#B3E5FC</td>
        <td bgcolor="#81D4FA">#81D4FA</td>
        <td bgcolor="#4FC3F7">#4FC3F7</td>
        <td bgcolor="#29B6F6">#29B6F6</td>
        <td bgcolor="#03A9F4">#03A9F4</td>
        <td bgcolor="#039BE5">#039BE5</td>
        <td bgcolor="#0288D1">#0288D1</td>
        <td bgcolor="#0277BD">#0277BD</td>
        <td bgcolor="#01579B">#01579B</td>
        <td bgcolor="#80D8FF">#80D8FF</td>
        <td bgcolor="#40C4FF">#40C4FF</td>
        <td bgcolor="#00B0FF">#00B0FF</td>
        <td bgcolor="#0091EA">#0091EA</td>
    </tr>
    <tr>
        <td>Cyan</td>
        <td bgcolor="#E0F7FA">#E0F7FA</td>
        <td bgcolor="#B2EBF2">#B2EBF2</td>
        <td bgcolor="#80DEEA">#80DEEA</td>
        <td bgcolor="#4DD0E1">#4DD0E1</td>
        <td bgcolor="#26C6DA">#26C6DA</td>
        <td bgcolor="#00BCD4">#00BCD4</td>
        <td bgcolor="#00ACC1">#00ACC1</td>
        <td bgcolor="#0097A7">#0097A7</td>
        <td bgcolor="#00838F">#00838F</td>
        <td bgcolor="#006064">#006064</td>
        <td bgcolor="#84FFFF">#84FFFF</td>
        <td bgcolor="#18FFFF">#18FFFF</td>
        <td bgcolor="#00E5FF">#00E5FF</td>
        <td bgcolor="#00B8D4">#00B8D4</td>
    </tr>
    <tr>
        <td>Teal</td>
        <td bgcolor="#E0F2F1">#E0F2F1</td>
        <td bgcolor="#B2DFDB">#B2DFDB</td>
        <td bgcolor="#80CBC4">#80CBC4</td>
        <td bgcolor="#4DB6AC">#4DB6AC</td>
        <td bgcolor="#26A69A">#26A69A</td>
        <td bgcolor="#009688">#009688</td>
        <td bgcolor="#00897B">#00897B</td>
        <td bgcolor="#00796B">#00796B</td>
        <td bgcolor="#00695C">#00695C</td>
        <td bgcolor="#004D40">#004D40</td>
        <td bgcolor="#A7FFEB">#A7FFEB</td>
        <td bgcolor="#64FFDA">#64FFDA</td>
        <td bgcolor="#1DE9B6">#1DE9B6</td>
        <td bgcolor="#00BFA5">#00BFA5</td>
    </tr>
    <tr>
        <td>Green</td>
        <td bgcolor="#E8F5E9">#E8F5E9</td>
        <td bgcolor="#C8E6C9">#C8E6C9</td>
        <td bgcolor="#A5D6A7">#A5D6A7</td>
        <td bgcolor="#81C784">#81C784</td>
        <td bgcolor="#66BB6A">#66BB6A</td>
        <td bgcolor="#4CAF50">#4CAF50</td>
        <td bgcolor="#43A047">#43A047</td>
        <td bgcolor="#388E3C">#388E3C</td>
        <td bgcolor="#2E7D32">#2E7D32</td>
        <td bgcolor="#1B5E20">#1B5E20</td>
        <td bgcolor="#B9F6CA">#B9F6CA</td>
        <td bgcolor="#69F0AE">#69F0AE</td>
        <td bgcolor="#00E676">#00E676</td>
        <td bgcolor="#00C853">#00C853</td>
    </tr>
    <tr>
        <td>Light_Green</td>
        <td bgcolor="#F1F8E9">#F1F8E9</td>
        <td bgcolor="#DCEDC8">#DCEDC8</td>
        <td bgcolor="#C5E1A5">#C5E1A5</td>
        <td bgcolor="#AED581">#AED581</td>
        <td bgcolor="#9CCC65">#9CCC65</td>
        <td bgcolor="#8BC34A">#8BC34A</td>
        <td bgcolor="#7CB342">#7CB342</td>
        <td bgcolor="#689F38">#689F38</td>
        <td bgcolor="#558B2F">#558B2F</td>
        <td bgcolor="#33691E">#33691E</td>
        <td bgcolor="#CCFF90">#CCFF90</td>
        <td bgcolor="#B2FF59">#B2FF59</td>
        <td bgcolor="#76FF03">#76FF03</td>
        <td bgcolor="#64DD17">#64DD17</td>
    </tr>
    <tr>
        <td>Lime</td>
        <td bgcolor="#F9FBE7">#F9FBE7</td>
        <td bgcolor="#F0F4C3">#F0F4C3</td>
        <td bgcolor="#E6EE9C">#E6EE9C</td>
        <td bgcolor="#DCE775">#DCE775</td>
        <td bgcolor="#D4E157">#D4E157</td>
        <td bgcolor="#CDDC39">#CDDC39</td>
        <td bgcolor="#C0CA33">#C0CA33</td>
        <td bgcolor="#AFB42B">#AFB42B</td>
        <td bgcolor="#9E9D24">#9E9D24</td>
        <td bgcolor="#827717">#827717</td>
        <td bgcolor="#F4FF81">#F4FF81</td>
        <td bgcolor="#EEFF41">#EEFF41</td>
        <td bgcolor="#C6FF00">#C6FF00</td>
        <td bgcolor="#AEEA00">#AEEA00</td>
    </tr>
    <tr>
        <td>Yellow</td>
        <td bgcolor="#FFFDE7">#FFFDE7</td>
        <td bgcolor="#FFF9C4">#FFF9C4</td>
        <td bgcolor="#FFF59D">#FFF59D</td>
        <td bgcolor="#FFF176">#FFF176</td>
        <td bgcolor="#FFEE58">#FFEE58</td>
        <td bgcolor="#FFEB3B">#FFEB3B</td>
        <td bgcolor="#FDD835">#FDD835</td>
        <td bgcolor="#FBC02D">#FBC02D</td>
        <td bgcolor="#F9A825">#F9A825</td>
        <td bgcolor="#F57F17">#F57F17</td>
        <td bgcolor="#FFFF8D">#FFFF8D</td>
        <td bgcolor="#FFFF00">#FFFF00</td>
        <td bgcolor="#FFEA00">#FFEA00</td>
        <td bgcolor="#FFD600">#FFD600</td>
    </tr>
    <tr>
        <td>Amber</td>
        <td bgcolor="#FFF8E1">#FFF8E1</td>
        <td bgcolor="#FFECB3">#FFECB3</td>
        <td bgcolor="#FFE082">#FFE082</td>
        <td bgcolor="#FFD54F">#FFD54F</td>
        <td bgcolor="#FFCA28">#FFCA28</td>
        <td bgcolor="#FFC107">#FFC107</td>
        <td bgcolor="#FFB300">#FFB300</td>
        <td bgcolor="#FFA000">#FFA000</td>
        <td bgcolor="#FF8F00">#FF8F00</td>
        <td bgcolor="#FF6F00">#FF6F00</td>
        <td bgcolor="#FFE57F">#FFE57F</td>
        <td bgcolor="#FFD740">#FFD740</td>
        <td bgcolor="#FFC400">#FFC400</td>
        <td bgcolor="#FFAB00">#FFAB00</td>
    </tr>
    <tr>
        <td>Orange</td>
        <td bgcolor="#FFF3E0">#FFF3E0</td>
        <td bgcolor="#FFE0B2">#FFE0B2</td>
        <td bgcolor="#FFCC80">#FFCC80</td>
        <td bgcolor="#FFB74D">#FFB74D</td>
        <td bgcolor="#FFA726">#FFA726</td>
        <td bgcolor="#FF9800">#FF9800</td>
        <td bgcolor="#FB8C00">#FB8C00</td>
        <td bgcolor="#F57C00">#F57C00</td>
        <td bgcolor="#EF6C00">#EF6C00</td>
        <td bgcolor="#E65100">#E65100</td>
        <td bgcolor="#FFD180">#FFD180</td>
        <td bgcolor="#FFAB40">#FFAB40</td>
        <td bgcolor="#FF9100">#FF9100</td>
        <td bgcolor="#FF6D00">#FF6D00</td>
    </tr>
    <tr>
        <td>Deep_Orange</td>
        <td bgcolor="#FBE9E7">#FBE9E7</td>
        <td bgcolor="#FFCCBC">#FFCCBC</td>
        <td bgcolor="#FFAB91">#FFAB91</td>
        <td bgcolor="#FF8A65">#FF8A65</td>
        <td bgcolor="#FF7043">#FF7043</td>
        <td bgcolor="#FF5722">#FF5722</td>
        <td bgcolor="#F4511E">#F4511E</td>
        <td bgcolor="#E64A19">#E64A19</td>
        <td bgcolor="#D84315">#D84315</td>
        <td bgcolor="#BF360C">#BF360C</td>
        <td bgcolor="#FF9E80">#FF9E80</td>
        <td bgcolor="#FF6E40">#FF6E40</td>
        <td bgcolor="#FF3D00">#FF3D00</td>
        <td bgcolor="#DD2C00">#DD2C00</td>
    </tr>
    <tr>
        <td>Brown</td>
        <td bgcolor="#EFEBE9">#EFEBE9</td>
        <td bgcolor="#D7CCC8">#D7CCC8</td>
        <td bgcolor="#BCAAA4">#BCAAA4</td>
        <td bgcolor="#A1887F">#A1887F</td>
        <td bgcolor="#8D6E63">#8D6E63</td>
        <td bgcolor="#795548">#795548</td>
        <td bgcolor="#6D4C41">#6D4C41</td>
        <td bgcolor="#5D4037">#5D4037</td>
        <td bgcolor="#4E342E">#4E342E</td>
        <td bgcolor="#3E2723">#3E2723</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>Grey</td>
        <td bgcolor="#FAFAFA">#FAFAFA</td>
        <td bgcolor="#F5F5F5">#F5F5F5</td>
        <td bgcolor="#EEEEEE">#EEEEEE</td>
        <td bgcolor="#E0E0E0">#E0E0E0</td>
        <td bgcolor="#BDBDBD">#BDBDBD</td>
        <td bgcolor="#9E9E9E">#9E9E9E</td>
        <td bgcolor="#757575">#757575</td>
        <td bgcolor="#616161">#616161</td>
        <td bgcolor="#424242">#424242</td>
        <td bgcolor="#212121">#212121</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>Blue_Grey</td>
        <td bgcolor="#ECEFF1">#ECEFF1</td>
        <td bgcolor="#CFD8DC">#CFD8DC</td>
        <td bgcolor="#B0BEC5">#B0BEC5</td>
        <td bgcolor="#90A4AE">#90A4AE</td>
        <td bgcolor="#78909C">#78909C</td>
        <td bgcolor="#607D8B">#607D8B</td>
        <td bgcolor="#546E7A">#546E7A</td>
        <td bgcolor="#455A64">#455A64</td>
        <td bgcolor="#37474F">#37474F</td>
        <td bgcolor="#263238">#263238</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>Black</td>
        <td bgcolor="#000000">#000000</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
    <tr>
        <td>White</td>
        <td bgcolor="#FFFFFF">#FFFFFF</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
        <td>N/A</td>
    </tr>
</table>
