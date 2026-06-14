



### I. Honest Disclaimer and Legal Acknowledgement
**Honest Disclaimer:** I possess absolutely zero technical expertise in this field, and this project should be treated as a collection of wild ideas rather than engineering advice. The vast majority of this documentation—including the deep technical architecture—was **Deeply Authored by Gemini + Google Search AI** functions. I am merely responsible for providing the initial "napkin sketches" and editing the AI's outputs for readability. Think of this as a "technical joke" that accidentally resulted in a modular hardware blueprint.
**Interaction Policy:** I will not be actively monitoring this project. If you manage to make this vision a reality, please "tag" (@) me in a GitHub Issue. I might receive an email notification—though it is also possible that I will be too busy with other projects to notice.
**Legal Disclaimer:** This project is provided "AS IS," without warranty of any kind, express or implied, including but not limited to the warranties of merchantability, fitness for a particular purpose, and non-infringement. In no event shall the authors or copyright holders be liable for any claim, damages, or other liability, whether in an action of contract, tort, or otherwise, arising from, out of, or in connection with the software or the use or other dealings in the software.
### 一、 誠實聲明與法律免責開場
**誠實聲明：** 本人對技術領域可謂一竅不通，這個專案的想法建議僅供參考，千萬別把它當成什麼嚴謹的工程指南。本文檔中絕大多數的內容——包含那些看起來很厲害的深度技術架構——皆由 **Gemini + Google 搜尋 AI 模式**功能深度撰寫 (Deeply Authored by Gemini+Google Search AI)。本人僅負責提供最初那種「在餐巾紙上塗鴉」等級的初步構想，以及後續無數次的內容修改。請把這當成是一個「意外變成模組化硬體藍圖的技術笑話」。
**互動設定：** 我不會主動監控此專案的動態。如果哪天這願景真的實現了，請在 GitHub Issue 中標記 (@) 我，屆時我或許會收到信件通知。然而，也很有可能當時我正忙於其他雜事，完全沒注意到您的標記。
**法律防禦：** 本專案依據「按現狀提供」(AS IS) 之條款授權，不提供任何形式的保證（包含但不限於適銷性、特定目的之適用性或不侵權性）。任何因本專案內容、使用或相關活動所導致的索賠、損害或其他責任，無論是基於合約、侵權行為或其他法律依據，作者或版權持有人概不負責。


### II. Core Project Vision: What is a Polymorphic Industrial Carrier?
**The Philosophy of Separating the "Brain" from the "Chassis":** Why do we repeat the cycle of buying a brand-new laptop every 2 to 3 years just because the CPU is outdated, while the keyboard, screen, and casing are still perfectly fine? This project aims to break the consumer electronics "black box" trap. We are creating a pure "infrastructure"—a physical carrier that possesses its own power and structure, completely decoupled from the computing core. Your smartphone, a tablet, or a Mac mini serves as the "brain," while this carrier provides the "body".
**Sensory Freedom (A Living Metaphor):** Think of traditional laptops as "packaged combo meals" from a fast-food chain—you cannot change the fries or the drink. This carrier is a "buffet."
 * **The Keyboard:** You can slide in your favorite 65% or 75% mechanical keyboard.
 * **The Trackpad:** Your smartphone screen can act as a high-precision trackpad via software, eliminating extra costs.
 * **The Upgradability:** When screen technology advances, you only replace the display module; when communication protocols upgrade, you only swap out the internal USB-C Hub. This is a commitment to a device you "buy once, use for ten years".
### 二、 專案核心願景：什麼是多態化工業載體？
**「大腦」與「軀殼」分離的哲學：** 為什麼我們每隔 2 到 3 年就得重複購買整台新筆電，只因為 CPU 變慢了，但明明鍵盤、螢幕和外殼都還好好的？本專案旨在打破消費電子產品的「黑盒子」陷阱。我們要創造的是一個純粹的「基礎設施」——一個自帶動力與結構、與運算核心完全解耦的物理載體。您的智慧型手機、平板電腦或 Mac mini 是「大腦」，而這個載體則提供「身體」。
**感官自由（生活化比喻）：** 傳統筆電就像速食店的「固定配餐」，你沒辦法單獨換掉薯條或飲料；而這個載體則是一個「自助餐」。
 * **鍵盤：** 您可以直接放入自己最愛的 60%、65% 或 75% 機械鍵盤。
 * **觸控板：** 直接用手機螢幕充當高精確度的觸控板，完全無需額外硬體成本。
 * **無損升級：** 當螢幕規格改朝換代時，您只需更換螢幕面板；當通訊協定升級時，您只需換掉托盤內的 USB-C Hub。這是一個「買一次，可以用十年」的硬體承諾。


### III. Deep Technical Architecture: Physical Form & Mechanical Assembly
**The Myth of the 3-Plate Folding Infrastructure:** Traditional laptops are fragile clamshells; this carrier is a heavy-duty industrial transformer. The architecture adopts a "Three-Plate Linkage" layout:
 * **The Screen Plate (Top):** Houses the display panel or acts as a universal rig for external tablets. It features dual industrial-grade **Linear Rails (MGN12H)**, allowing smooth vertical height adjustments to eliminate neck strain without relying on flimsy plastic hinges.
 * **The Battery Spine (Center):** Anchored by two high-torque **Southco Constant Torque Hinges (ST-11L, 5Nm class)**, this component stands perpendicular to the desk. It acts as the backbone of the entire machine, suspending a massive heavy-duty 21700 battery array right in the middle of the structure.
 * **The Tray Base (Bottom):** Sits flat on the desk, providing a recessed tray for mechanical keyboards, integrated cable management, and heavy I/O breakout boxes.
**The "Beyond-Vertical" Center of Mass Balancing Act (A Living Metaphor):** Why doesn't it tip over when the heavy screen is extended upwards? It relies on the physics of a **"Rear-Tilt Stabilization Structure."** Think of it as an Olympic weightlifter leaning their torso slightly backward to stabilize a barbell overhead. When the screen moves up, the Battery Spine is tilted backward past the vertical plane (100^\circ \text{--} 110^\circ). The massive gravity of the 21700 cells pulls the combined center of mass directly over the geometric center of the Base Tray, making the entire setup rock-solid.
**The Chimney Effect Passive Thermal Architecture:** By flipping the battery cells and internal electronics onto a vertical plane (the Spine), we completely eliminate the thermal choking common in modern laptops. Since hot air naturally rises, the vertical alignment creates a textbook **"Chimney Effect."** Cold air enters from the bottom gap of the chassis, sweeps across the battery array and charging modules, and escapes out the top naturally—achieving exceptional cooling performance with zero fan noise.
### 三、 深度技術架構：物理形態與力學組裝
**三片式摺疊架構的狂想：** 傳統筆電是脆弱的蚌殼；而這個載體則是重型工業變形金剛。本架構採用了創新的「三片式連動」佈局：
 * **螢幕片 (Top)：** 內嵌顯示面板或作為外掛平板的萬能夾具。其表面配置了兩條工業級的 **MGN12H 線性滑軌**，提供滑順的垂直升降功能，讓人不用低頭看螢幕，徹底告別傳統筆電那種弱不禁風的塑料轉軸。
 * **電池支撐片 (Spine)：** 由兩顆強悍的 **Southco 恆定扭力轉軸 (ST-11L，5Nm級阻尼)** 牢牢固定，垂直於桌面立起。它是整台機器的「脊椎」，將沉重的 21700 動力電池陣列高高懸掛在結構正中央。
 * **托盤片 (Base)：** 平貼於桌面，提供機械鍵盤凹槽、捲線空間以及重型 I/O 集線區。
**「超越垂直」的重心平衡（生活化比喻）：** 為什麼螢幕拉高時機器不會往後倒？這完全仰閱物理學上的**「後傾穩定結構」**。想像一位奧運舉重選手，為了在頭頂撐起槓鈴，身體會自然稍微後仰以維持平衡。當螢幕向上滑動時，中央的電池支撐片會「超越垂直角度」向後傾斜（約 100^\circ \text{--} 110^\circ）。此時，垂直面上的 21700 電池重力會化身為天然的配重沙包，將整機重心牢牢壓在底座托盤的幾何中心點，穩如泰山。
**煙囪效應的垂直散熱架構：** 我們把所有發熱源（電池、快充模組）全部轉移到了垂直的「脊椎片」上，徹底解決了傳統筆電平躺散熱的窒息問題。利用熱空氣自然上升的物理天性，這種垂直排列直接觸發了教科書等級的**「煙囪效應」**。冷空氣從主機底部空隙吸入，順著垂直表面帶走電池與電路板的廢熱，再從頂端自然排出——達成零風扇噪音的極致被動散熱。


### IV. Zero Machining & Brick-Style Modular Standards
**The Absolute Zero Machining Philosophy (A Living Metaphor):** Building a custom laptop casing usually requires expensive CNC milling or professional injection molding. This project rejects all of that. We are building a hardware system using an approach similar to LEGO. Every single structural component relies entirely on off-the-shelf **1515 T-Slot Aluminum Extrusions**. There is absolutely no drilling, no cutting, and no custom metal fabrication required. If you can use a hex key, you can assemble this industrial chassis.
**The Magic of Universal T-Slots & Anti-Machining Anchors:**
 * **Infinite Locking Interfaces:** Every component, from the internal circuit board to the massive display hinges, is anchored by sliding a **T-Nut** into the 1515 extrusion groove and securing it with standard M3 or M4 screws.
 * **COTS Interface Ports:** To expose I/O ports without cutting custom rectangular cutouts, we use off-the-shelf **multi-hole stainless steel L-brackets** (corner braces). Flush-mount USB-C extension cables with integrated screw ears are locked onto these L-brackets, which are then secured directly into the T-slots.
 * **Non-Structural Shock Absorption:** Internal components that do not experience heavy mechanical stress—such as the USB-C Hub or battery brackets—are attached using **3M VHB industrial double-sided foam tape** or heavy-duty hook-and-loop fasteners. This eliminates complex custom mounts while providing excellent shock and vibration isolation.
**Hardware Containerization and The 100mm Modular Scale:** The physical chassis length is defined using a standard multiplier logic to completely eliminate arbitrary millimeter-level custom cuts. The system sets **100mm as the Standard Hardware Container Unit** and **50mm as the Base Structural Increment**.
 * **The Physics of Short-Piece Stitching:** Instead of buying single, long custom-milled aluminum crossbeams, the internal electronics bays are stitched together using standard 100mm prefabricated segments.
 * **The Exoskeleton Rigidity Effect:** To prevent sagging or accumulated mechanical tolerances across these short segments, the joints are reinforced using long structural COTS components—such as the **300mm MGN linear steel rails** or the battery array's steel backplate—as heavy-duty external splices. When the final rectangular frame closes and bolts down, the structural rigidity increases exponentially via this structural exoskeleton effect, delivering industrial-grade stiffness.
### 四、 零加工（Zero Machining）與積木化實施標準
**絕對零加工的哲學（生活化比喻）：** 製造客製化的筆電外殼通常需要昂貴的 CNC 銑床加工或專業的開模注塑。本專案徹底拒絕這種高門檻。我們是用「樂高積木」的方式在組裝硬體。全機的結構完全依賴現成的 **1515 T 型槽鋁擠型**。這裡絕對不需要任何鑽孔、不需車床銑床、也不需要任何訂製金屬件。只要你會用六角扳手，你就能組裝出這個工業載體。
**萬能 T 型槽與反加工鎖點的魔術：**
 * **無限擴充介面：** 從內部的電路板到沉重的顯示器轉軸，所有組件都是透過將 **T 型螺母**滑入 1515 鋁擠型的溝槽內，再用標準的 M3 或 M4 螺絲直接鎖固。
 * **現成五金替代接口面板：** 為了在不開出複雜長方形面板孔的前提下固定對外接口，我們採用市售現成的**多孔不鏽鋼 L 型固定角材**。將帶螺絲固定耳的母對母 USB-C 面板線鎖在 L 片上，再將 L 片直接鎖入鋁擠型溝槽，就成了一個現成的穩固接口。
 * **非結構件的減震黏合：** 內部不需要承受巨大機械應力的組件——例如 USB-C Hub 或電池盒固定座——一律使用 **3M VHB 工業級強力雙面膠**或重型魔鬼氈直接黏貼在鋁材上。這免去了複雜的客製化夾具，同時提供了極佳的物理防震緩衝。
**硬體容器化與 100mm 標準倍率積木化：** 主機的物理尺寸完全由標準倍率邏輯定義，從根本上抹除任意毫米級的訂製裁切。本系統定義 **100mm 為標準硬體容器單元（Standard Container）**，**50mm 為基礎結構單位**。
 * **短件拼接的物理學：** 內部的功能艙體完全拆解為最小公約數。不使用單一長條的訂製鋁材橫梁，而是由標準 100mm 的預裁切短鋁材拼湊而成。
 * **外骨骼剛性效應：** 為了消除短件鋁材拼接產生的累積公差與晃動，拼接處會利用橫跨接縫的長條型現成鋼製零件——例如 **300mm 的 MGN 線性鋼製滑軌**或電池組的鋼製背板——充當重型「外夾板」共同鎖固。當整個矩形框體閉合鎖緊後，整體的扭轉剛性將透過外骨骼效應呈幾何倍數提升，達到工業級剛性。



### V. Segmented Armor & Hidden Fastener Aesthetics (The Lab Look)
**The "Instrument Grade" Aesthetic:** We are not chasing the sleek, fragile look of a MacBook. Instead, we are aiming for the "Hardcore Lab" aesthetic—think Leica cameras, RED cinema rigs, or blade servers. The device doesn't just "work"; it looks like it was built to survive a lab experiment or a field deployment.
**The Power of Segmented Armor Panels:** Each 100mm standard modular unit is covered by an independent, precision-cut metal plate (100\text{mm} \times 45\text{mm}).
 * **Visual Rhythm:** By treating each functional艙位 (compartment) separately, we create a rhythmic visual texture. You can finish the "Energy Bay" in matte dark grey sandblasted aluminum and the "Signal Bay" in brushed silver, clearly signaling the device's functional zones.
 * **Serviceability:** If a charging module needs an upgrade, you don't disassemble the whole machine—you only unscrew the four fasteners on the specific panel, keeping the rest of the unit intact.
**Hidden Fasteners (The "Unibody" Trick):** To achieve the clean, premium look of a unibody device despite using a bolted-together aluminum frame, we employ a "Hidden Fastener" technique:
 * **The Reverse-Bolt Strategy:** All panels feature "Self-Clinching Nuts" (PEM nuts) pre-installed on the backside. Bolts are inserted from the *inside* of the aluminum extrusion's inner cavity and screwed outward into the panels.
 * **The Visual Result:** Viewed from the outside, the chassis is a seamless, cold-metal shell with zero visible screw heads. All assembly marks and cable clutter are neatly hidden within the internal "spine" cavity, preserving that mysterious, high-end scientific instrument finish.
### 五、 分片裝甲與隱藏式內鎖美學（The Lab Look）
**「儀器級」的視覺美學：** 我們追求的不是 MacBook 那種輕薄脆弱的消費級質感，而是「硬核實驗室」風格——類似徠卡相機、電影攝影機或刀鋒伺服器的那種質感。設備不僅僅是「能用」，看起來更像是為了應對精密實驗或嚴苛的現場環境而生的。
**分片式裝甲面板：** 每一段 100mm 的標準模組，上方都獨立鎖上一片精密裁切的金屬面板（100\text{mm} \times 45\text{mm}）。
 * **視覺節奏感：** 將每個功能艙位（艙體）分開處理，能創造出強烈的物理節奏。例如，「能源艙」可以採用深灰色噴砂鋁板，而「訊號艙」則使用拉絲銀面板，這種視覺分區能讓使用者一眼辨識機器的功能配置。
 * **局部維修性：** 如果電力模組需要升級，您完全不需要拆解整台機器，只需轉開該特定面板上的 4 顆螺絲，就能局部更換，保持結構的完整性。
**隱藏式緊固（「一體化」的障眼法）：** 為了在鋁擠型拼裝架構下，實現 Unibody（一體成型）般的高級洗鍊感，我們採用了「隱藏式緊固」技術：
 * **逆向鎖固策略：** 所有面板背後都預先安裝「背柱螺母（Self-Clinching Nuts）」。螺絲由鋁擠型的內腔「由內向外」穿出，鎖入面板背後的螺母。
 * **視覺效果：** 從外部看去，整台機器的外殼是一整片乾淨、冷冽的金屬護甲，沒有任何一顆外露的螺絲頭。所有的組裝痕跡與內部的雜亂線材，通通被完美隱藏在內腔的「脊椎」結構中，展現出高階科學儀器那種神秘又嚴謹的美感。




### VI. Local Procurement & Bill of Materials (BOM) - Taiwan Edition
**Procurement Philosophy (The "Buffet" Logic):** We avoid custom factory orders. Every single item in this BOM is a "Commercial Off-The-Shelf" (COTS) product available from suppliers like **Misumi Taiwan**, **Shopee**, or local electronics retailers. The total estimated budget is between **NT$ 6,000 – 9,500**, depending on your choice of high-end Hubs or specialized hinges.

| Category | Component | Spec/Description | Qty | Est. Cost (NTD) |
| :--- | :--- | :--- | :--- | :--- |
| **Structure** | 1515 Aluminum Extrusion | Standardized segments (100\text{mm}/50\text{mm} multipliers) | 1 set | $400 - 600 |
| **Mechanics** | Southco Constant Torque Hinge | ST-11L (5Nm class, industrial grade) | 2 | $800 - 1,200 |
| **Motion** | MGN Linear Rail | MGN12H + 300mm Steel Rail | 2 | $500 - 900 |
| **Fasteners** | T-Nuts & Screws | M3/M4 standard set, L-brackets | 1 pack | $500 - 800 |
| **Energy** | PD Charging Module | IP5389 100W Bidirectional w/ Screen | 1 | $450 - 650 |
| **Battery** | 21700 Li-ion Cells | High-drain cells (Samsung/LG equivalent) | 14 | $1,200 - 1,600 |
| **Data** | 10Gbps USB-C Hub | Slim, multi-port, non-Ethernet version | 1 | $800 - 1,500 |
| **Interface** | Panel Cables | USB-C Mother-to-Mother (screw-ear mount) | 4 | $300 - 400 |
| **Finishing** | Custom Plates | 100x45mm Sandblasted/Brushed Aluminum | 4 | $300 - 500 | <br> *Note: Prices are estimates based on Taiwan local market availability as of mid-2026. Costs may fluctuate based on specific brand preferences.* <br> ### 六、 台灣在地零組件推薦配置與預算表（BOM） <br> **採購哲學（自助餐邏輯）：** 我們徹底摒棄「開模訂製」，本清單上的每一個零件都是可直接從**台灣米思米 (Misumi)**、**蝦皮 (Shopee)** 或電子零件商行購得的現成組件（COTS）。總預算控制在 **新台幣 6,000 元至 9,500 元** 之間，具體取決於您選用的 Hub 等級與五金品牌。
| 分類 | 零件名稱 | 建議規格與描述 | 數量 | 估算預算 (NTD) |
| :--- | :--- | :--- | :--- | :--- |
| **結構** | 1515 鋁擠型 | 標準倍率件拼湊 (100\text{mm} / 50\text{mm}) | 1 套 | $400 - 600 |
| **機械** | Southco 恆定扭力轉軸 | ST-11L (5Nm級，工業級強度) | 2 個 | $800 - 1,200 |
| **運動** | MGN 線性滑軌 | MGN12H + 300\text{mm} 鋼軌 | 2 組 | $500 - 900 |
| **緊固** | T 型螺母/螺絲組 | M3/M4 標準包、L 型固定角材 | 1 包 | $500 - 800 |
| **能源** | PD 快充模組 | IP5389 100W 雙向帶螢幕版 | 1 個 | $450 - 650 |
| **電池** | 21700 動力鋰電池 | 高倍率動力芯 (三星/LG 等級) | 14 顆 | $1,200 - 1,600 |
| **數據** | 10Gbps USB-C Hub | 薄型、多口、無網口版本 | 1 個 | $800 - 1,500 |
| **介面** | 帶耳面板線 | USB-C 母對母 (含螺絲固定耳) | 4 條 | $300 - 400 |
| **外觀** | 分片裝甲面板 | 100 \times 45\text{mm} 噴砂/拉絲鋁板 | 4 片 | $300 - 500 |

*註：以上價格為預估值，取決於採購時的市場行情與特定品牌選擇。*


### VII. Legal Defense & License Terms
**License: Apache License 2.0**
This project is released under the **Apache License 2.0**. This means you are free to use, modify, and distribute the design. However, there are mandatory legal disclaimers that protect the original contributors.
**Disclaimer of Liability (The "AS IS" Clause):**
TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW, THIS PROJECT IS PROVIDED "AS IS" AND "AS AVAILABLE," WITHOUT ANY REPRESENTATION OR WARRANTY OF ANY KIND. THE AUTHORS AND COPYRIGHT HOLDERS EXPRESSLY DISCLAIM ALL WARRANTIES, WHETHER EXPRESS, IMPLIED, OR STATUTORY, INCLUDING BUT NOT LIMITED TO ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, OR NON-INFRINGEMENT.
**Risk Warning:** Building hardware involves handling electrical components, batteries, and mechanical parts. The author is not responsible for any personal injury, property damage, fire, or data loss arising from the use or implementation of this design. **Build at your own risk.**
### 七、 法律防禦與授權條款
**授權：Apache License 2.0**
本專案採用 **Apache License 2.0** 授權釋出。這代表您可以自由使用、修改並散佈本設計。然而，為了保護原始貢獻者，我們必須包含強制的法律免責條款。
**責任免除（「按現狀提供」條款）：**
在適用法律所允許的最大範圍內，本專案係按「現狀」(AS IS) 及「現有」(AS AVAILABLE) 之基礎提供，不提供任何形式之明示或默示之保證。作者與版權持有人明確聲明拋棄所有保證（無論是明示、默示或法定），包含但不限於對適銷性、特定目的之適用性，或不侵犯他人權利之擔保。
**風險警告：**
硬體建置涉及處理電力組件、鋰電池與機械結構。若因使用或實作本設計而導致之人身傷害、財產損失、火災風險或數據遺失，作者概不負責。**請務必自行承擔所有組裝風險。**




### VIII. Appendix Information
**[Project Description]**
An open-standard, modular industrial carrier system for electronics. Utilizing standardized 1515 T-Slot aluminum profiles and a "Zero Machining" assembly logic, this project provides a rugged, highly modular, and aesthetically "hardcore" physical infrastructure for computing devices, decoupling the computing "brain" from the structural "chassis."
**[Topics]**
hardware-open-source modular-design industrial-design cyberdeck t-slot-aluminum diy-electronics portable-workstation zero-machining
**[SEO Keywords]**
Open-source hardware carrier, modular aluminum laptop chassis, zero-machining hardware design, custom DIY workstation, 1515 T-slot modular system, hardcore industrial aesthetic, DIY cyberdeck, portable computing infrastructure, open hardware project, custom electronic enclosure.
### 八、 附件資訊
**[專案描述 (GitHub About 欄位)]**
一個開放標準、模組化的工業級電子載體系統。利用標準化的 1515 T 型槽鋁擠型與「零加工」組裝邏輯，為運算設備提供堅固、高度模組化且具備「硬核」工業美學的物理基礎設施，實現運算「大腦」與物理「載體」的徹底解耦。
**[Topics 標籤 (GitHub 搜尋標籤)]**
開放硬體 模組化設計 工業設計 Cyberdeck 鋁擠型 電子 DIY 移動工作站 零加工
**[SEO 關鍵字 (給搜尋引擎看的關鍵字)]**
開放硬體載體, 模組化鋁合金筆電支架, 零加工硬體設計, 客製化 DIY 工作站, 1515 T型槽系統, 硬核工業美學, DIY Cyberdeck, 移動運算基礎設施, 開放硬體專案, 電子設備外殼訂製.






















































































































