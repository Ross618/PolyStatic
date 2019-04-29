<template>
  <div class="page">
    <div class="box">
      <div class="__content" style="text-align:center">
        <h1>Our<span class="highlight"> Products</span></h1>
        <p style="font-size: 1.4rem;">
          PolyTherm offers a wide range of plastic recycling machinery.
        </p>
      </div>
    </div>

  <div class="prod">
    <div class="headline">
      <h1>Plastic Recycling Machinery</h1>
    </div>
    <div class="__icons">
      <div class="__icon" :class="{ '__expand' : toggleCat }" @click="toggleCategory()">
      <h2>KE-180 Base Material Edge Trimming Film Recycling Unit</h2> 
      <img src='../assets/images/KE-180 Base Material Edge Trimming Film Recycling Unit.jpg' :class="{ '__expand' : toggleCat }" alt="Base Material Edge Trimming Film Recycling Unit">
        <transition name="expand">
        <div class="category" v-if="toggleCat">
          <div class="product-info">
            <h1>KE-180 Base Material Edge Trimming Film Recycling Unit</h1>
            <p><strong>Working Priciple:</strong></p>
            <p>The rim charges of membrane get into pressing unit through feeding unit. After solid pressing, the rim charges are transmitted into cutting unit for granule cutting.</p>
            <p><strong>Application:</strong></p>
            <p>CPE, PE, CPP, PO, PP, EVA, BOPA, POF, LLDPE, TPE, and nonwoven, etc.</p>
            <table class="prod-table">
            <tr>
              <th>Item</th>
              <th>KE-180 recycling unit</th>
              <th>Plastic crushing machine</th>
              <th>Plastic recycling machine</th>
            </tr>
            <tr>
              <td>Recycle mode</td>
              <td>Cutting and shaped</td>
              <td>Crushing</td>
              <td>Heating up and shaped</td>
            </tr>
            <tr>
              <td>Product shape</td>
              <td>Slice granule</td>
              <td>Slice powder</td>
              <td>granule</td>
            </tr>
            <tr>
              <td>Chemistry performance</td>
              <td>Identical with original</td>
              <td>Identical</td>
              <td>No identical</td>
            </tr>
            <tr>
              <td>Max.accession amount</td>
              <td>30%-40%</td>
              <td>5%-10%</td>
              <td>10%-15%</td>
            </tr>
            <tr>
              <td>Operation method</td>
              <td>Single or online</td>
              <td>Single, no online</td>
              <td>Complex, no online</td>
            </tr>
            <tr>
              <td>General power</td>
              <td>2-3kw</td>
              <td>7kw</td>
              <td>40kw</td>
            </tr>
            <tr>
              <td>Capacity</td>
              <td>100-150kg/hr</td>
              <td>180-250kg/hr</td>
              <td>80-250kg/hr</td>
            </tr>
            <tr>
              <td>Cleaniness</td>
              <td>No polluted</td>
              <td>No polluted</td>
              <td>Be polluted as its complex work</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>

      <div class="__icon" :class="{ '__expand' : toggleCat2 }" @click="toggleCategory2()">
      <h2>PE PP film washing line</h2>
      <img src='../assets/images/PEPP-film-washing.jpg' :class="{ '__expand' : toggleCat2 }" alt="PEPP-film-washing">
      <transition name="expand">
        <div class="category" v-if="toggleCat2">
          <div class="product-info">
            <h1>PE PP film washing line</h1>
            <p><strong>Working Flow:</strong></p>
            <p>Belt conveyor * 2 → Crusher * 2 → Screw conveyor* 2 → Floating washer → High speed friction machine → Screw conveyor →  Horizontal dewatering machine → Drying pipe system → Transition storage  → Drying pipe system →Storage hopper → Control cabinet</p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>Capacity (kg/h)</th>
              <th>Power Consumption (kw)</th>
              <th>Water Consumption (ton/h)</th>
              <th>Manpower</th>
              <th>Humidity Content</th>
            </tr>
            <tr>
              <td>MPE-300</td>
              <td>300kg/hour</td>
              <td>125kw</td>
              <td>3ton/h</td>
              <td>3</td>
              <td>≤5%</td>
            </tr>
            <tr>
              <td>MPE-500</td>
              <td>500kg/hour</td>
              <td>260kw</td>
              <td>4-5ton/h</td>
              <td>3</td>
              <td>≤5%</td>
            </tr>
            <tr>
              <td>MPE-1000</td>
              <td>1000kg/hour</td>
              <td>395kw</td>
              <td>6ton/h</td>
              <td>4</td>
              <td>≤5%</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggleCat3 }" @click="toggleCategory3()">
      <h2>HDPE, PP bottle, container, crate, barrel washing line</h2>
      <img src='../assets/images/HDPE.jpg' :class="{ '__expand' : toggleCat3 }">
      <transition name="expand">
        <div class="category" v-if="toggleCat3">
          <div class="product-info">
            <h1>HDPE, PP bottle, container, crate, barrel washing line</h1>
            <p><strong>Working Flow:</strong></p>
            <p>Belt conveyor → Crusher  → Screw conveyor → （Hot）Floating washer → Screw conveyor →  Vertical dewatering machine → Drying pipe system → Zig Zag air classification system →Storage hopper → Control cabinet</p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>Capacity (kg/h)</th>
              <th>Power Consumption (kw)</th>
              <th>Water Consumption (ton/h)</th>
              <th>Manpower</th>
              <th>Humidity Content</th>
            </tr>
            <tr>
              <td>MPB-300</td>
              <td>300kg/hour</td>
              <td>175kw</td>
              <td>3ton/h</td>
              <td>3</td>
              <td>＜1%</td>
            </tr>
            <tr>
              <td>MPB-500</td>
              <td>500kg/hour</td>
              <td>200kw</td>
              <td>4-5ton/h</td>
              <td>3</td>
              <td>＜1%</td>
            </tr>
            <tr>
              <td>MPB-1000</td>
              <td>1000kg/hour</td>
              <td>295kw</td>
              <td>6ton/h</td>
              <td>4</td>
              <td>＜1%</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggleCat4 }" @click="toggleCategory4()">
      <h2>Pet bottle washing line</h2>
      <img src='../assets/images/pet-bottle-washing.jpg' :class="{ '__expand' : toggleCat4 }">
      <transition name="expand">
        <div class="category" v-if="toggleCat4">
          <div class="product-info">
            <h1>Pet bottle washing line</h1>
            <p><strong>Working Flow:</strong></p>
            <p>Belt conveyor → Roll separator → Belt conveyor → Mechanical label remover → Manual separating table → Metal detector →Belt conveyor → Crusher → Screw conveyor → High speed friction machine → Screw conveyor → Floating washer → Screw conveyor → Hot washer → Screw conveyor → Floating washer → Screw conveyor → Vertical dewatering machine → Drying pipe system → Zig zag air classification system → Storage hopper → Control cabinet</p>
            <h4>Estimated Plant Parameters:</h4>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>Capacity (kg/h)</th>
              <th>Power Consumption (kw)</th>
              <th>Water Consumption (ton/h)</th>
              <th>Manpower</th>
              <th>Humidity Content</th>
            </tr>
            <tr>
              <td>MT-300</td>
              <td>300kg/hour</td>
              <td>150kw</td>
              <td>3ton/h</td>
              <td>4</td>
              <td>＜1%</td>
            </tr>
            <tr>
              <td>MT-500</td>
              <td>500kg/hour</td>
              <td>230kw</td>
              <td>4-5ton/h</td>
              <td>4</td>
              <td>＜1%</td>
            </tr>
            <tr>
              <td>MT-1000</td>
              <td>1000kg/hour</td>
              <td>270kw</td>
              <td>6-7ton/h</td>
              <td>4</td>
              <td>＜1%</td>
            </tr>
            <tr>
              <td>MT-2000</td>
              <td>2000kg/hour</td>
              <td>370kw</td>
              <td>8ton/h</td>
              <td>4</td>
              <td>＜1%</td>
            </tr>
          </table>
          <h4>PET Flakes Quality Reference:</h4>
            <table class="prod-table">
            <tr>
              <th>No.</th>
              <th>Description</th>
              <th>AA level (ppm)</th>
              <th>A level (ppm)</th>
            </tr>
            <tr>
              <td>1</td>
              <td>PVC content</td>
              <td>≤25</td>
              <td>≤100</td>
            </tr>
            <tr>
              <td>2</td>
              <td>PE/PP color flake/metal and other impurity content</td>
              <td>≤75</td>
              <td>≤100</td>
            </tr>
            <tr>
              <td>3</td>
              <td>Total impurity</td>
              <td>≤100</td>
              <td>≤200</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggleCat5 }" @click="toggleCategory5()">
      <h2>SJ single-stage PEPP film pelletizing line</h2>
      <img src='../assets/images/SJ single-stage PEPP film pelletizing line.jpg' :class="{ '__expand' : toggleCat5 }">
      <transition name="expand">
        <div class="category" v-if="toggleCat5">
          <div class="product-info">
            <h1>SJ single-stage PEPP film pelletizing line</h1>
            <p><strong>Consist of:</strong></p>
            <p>Side feeder → Extruder → Hydraulic screen changer → Water ring cutting system →Dewatering machine → Air blow system → Storage</p>
            <p>(Note, our SJ series granulator can be pull strip cutting method, or water ring cutting method for option)</p>
            <p><strong>Application:</strong></p>
            <p>PE, PP film, Flakes, etc.</p>
            <table class="prod-table">
            <tr>
              <th>Model (single-stage)</th>
              <th>SJ-65</th>
              <th>SJ-80</th>
              <th>SJ-100</th>
              <th>SJ-120</th>
              <th>SJ-150</th>
              <th>SJ-200</th>
            </tr>
            <tr>
              <td>Screw Diameter (mm)</td>
              <td>65</td>
              <td>80</td>
              <td>100</td>
              <td>120</td>
              <td>150</td>
              <td>200</td>
            </tr>
            <tr>
              <td>L/D</td>
              <td>28-30</td>
              <td>28-30</td>
              <td>28-30</td>
              <td>28-30</td>
              <td>28-30</td>
              <td>28-30</td>
            </tr>
            <tr>
              <td>Capacity(kg/h)</td>
              <td>60-80kg/hour</td>
              <td>80-100 kg/hour</td>
              <td>100-150kg/h</td>
              <td>200-300kg/h</td>
              <td>300-400kg/h</td>
              <td>400-550kg/h</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>

      <div class="__icon" :class="{ '__expand' : toggleCat6 }" @click="toggleCategory6()">
      <h2>TSSK series parallel twin screw extruder</h2>
      <img src='../assets/images/TSSK series parallel twin screw extruder.jpg' :class="{ '__expand' : toggleCat6 }">
      <transition name="expand">
        <div class="category" v-if="toggleCat6">
          <div class="product-info">
            <h1>TSSK series parallel twin screw extruder</h1>
            <p><strong>Consists of:</strong></p>
            <p>Feeder → TSSK series Parallel twin screw extruder → Hydraulic screen changer →Cooling tank→ Air drying → Cutter</p>
            <p><strong>Application:</strong></p>
            <p>TSSK parallel twin screw extruder can directly convert thermoplastic filler, compounding, modified, degassing, stability of coloring and granulation equally. It is ideal machine for polymer industry. It is also used for PET flake pelletizing.</p>
            <h4>TSSK Series of Granulator Parameters:</h4>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>TSSK-50</th>
              <th>TSSK-65</th>
              <th>TSSK-75</th>
              <th>TSSK-92</th>
            </tr>
            <tr>
              <td>Screw Diameter (mm)</td>
              <td>50.0</td>
              <td>62.4</td>
              <td>71.2</td>
              <td>91</td>
            </tr>
            <tr>
              <td>Motor Power (kw)</td>
              <td>37/45</td>
              <td>55/75</td>
              <td>90/110</td>
              <td>220/250</td>
            </tr>
            <tr>
              <td>L/D</td>
              <td>32-48</td>
              <td>32-48</td>
              <td>32-48</td>
              <td>32-40</td>
            </tr>
            <tr>
              <td>Capacity(kg/h)</td>
              <td>20-150kg/hour</td>
              <td>100-300 kg/hour</td>
              <td>300-600kg/h</td>
              <td>600-1000kg/h</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>

      <div class="__icon" :class="{ '__expand' : toggleCat7 }" @click="toggleCategory7()">
      <h2>ZL single-stage PEPP film compactor-pelletizing line</h2>
      <img src='../assets/images/ZL single-stage PEPP film compactor-pelletizing line.jpg' :class="{ '__expand' : toggleCat7 }">
      <transition name="expand">
        <div class="category" v-if="toggleCat7">
          <div class="product-info">
            <h1>ZL single-stage PEPP film compactor-pelletizing line</h1>
            <p><strong>Consists of:</strong></p>
            <p>Belt conveyor(metal detector) → Compactor → Extruder(vacuum degassing system) → Hydraulic screen changer → Water ring cutting system →Dewatering machine → Air blow system → Storage</p>
            <p>(Note, our ZL series compactor granulator can be pull strip cutting method, or water ring cutting method for option)</p>
            <p><strong>Application:</strong></p>
            <p>PE, PP film, Silk, Flakes(≤0.5mm), Bags,  etc.</p>
            <h4>ZL Series of Compactor-Granulator Parameters:</h4>
            <table class="prod-table">
            <tr>
              <th>Model (single-stage)</th>
              <th>ZL-85</th>
              <th>ZL-100</th>
              <th>ZL-130</th>
              <th>ZL-160</th>
              <th>ZL-180</th>
            </tr>
            <tr>
              <td>Screw Diameter (mm)</td>
              <td>85</td>
              <td>100</td>
              <td>130</td>
              <td>160</td>
              <td>180</td>
            </tr>
            <tr>
              <td>L/D</td>
              <td>25-42</td>
              <td>25-42</td>
              <td>25-33</td>
              <td>25-33</td>
              <td>25-33</td>
            </tr>
            <tr>
              <td>Capacity(kg/h)</td>
              <td>120-150kg/hour</td>
              <td>250-350 kg/hour</td>
              <td>400-500kg/h</td>
              <td>600-700kg/h</td>
              <td>800-1000kg/h</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>

    </div>
  </div>

  <div class="prod">
    <div class="headline">
      <h1>Plastic Pipe/profile Extrusion Line</h1>
    </div>
    <div class="__icons">
      <div class="__icon" :class="{ '__expand' : toggle2Cat }" @click="toggle2Category()">
      <h2>Drip irrigation belt line</h2> 
      <img src='../assets/images/Drip irrigation belt line.jpg' :class="{ '__expand' : toggle2Cat }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat">
          <div class="product-info">
            <h1>Drip irrigation belt line</h1>
            <p>DGD SERIES DRIP IRRIGATION BELT PRODUCTION LINE</p>
            <p><strong>Technical features</strong></p>
            <p>1. The production line adopts high efficiency extruder, swift net changer and screw plastic blowing head;</p>
            <p>2. Special designed vacuum composite forming die to ensure the accuracy and composite density;</p>
            <p>3. Unique measure device and scale huff to ensure the precise of products;</p>
            <p>4. Extruder and haul-off adopt AC frequency conversion technology;</p>
            <p>5. Temperature is adjusted by temperature control meter to realize PID control;</p>
            <p>6. The production is controlled by PLC, all the technical parameters can be set on the touch screen;</p>
            <p><strong>Main Parameters</strong></p>
            <table class="prod-table">
            <tr>
              <td>Production speed (m/min)</td>
              <td>24-60</td>
            </tr>
            <tr>
              <td>Hole Dia. (mm)</td>
              <td>16mm</td>
            </tr>
            <tr>
              <td>Belt thickness (mm)</td>
              <td>0.16,? 0.18</td>
            </tr>
            <tr>
              <td>Distance (mm)</td>
              <td>100，200,? 300,? 400，600</td>
            </tr>
            <tr>
              <td>Roller length (m)</td>
              <td>500-2000</td>
            </tr>
            <tr>
              <td>Total power consumption (kw)</td>
              <td>32</td>
            </tr>
          </table>
          <p>Drip irrigation line is used for production single wall labyrinth water conveying belt on the base of polyelefin. It is used in green houses and farms.</p>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle2Cat2 }" @click="toggle2Category2()">
      <h2>PE-XA pipe line</h2> 
      <img src='../assets/images/PE-XA pipe line.jpg' :class="{ '__expand' : toggle2Cat2 }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat2">
          <div class="product-info">
            <h1>PE-XA pipe line</h1>
            <p><strong>Process flow:</strong></p>
            <p>Raw material+ additive → mixing → conveying feeding → plunger stamping extruder → mould →ink printer → cooling water tank → haul-off → meter measurer → winder → manual cut → finished product inspecting & packing</p>
            <p><strong>Application:</strong></p>
            <p>Application of PE-XA pipe include indoor water-supply pipe, hot water pipe, pure water, the liquid food sending pipeline in food industry; heating system of the hot-water heating central air conditional pipeline system; telecommunications, electroplate, petrol eum, chemical sending pipeline system and etc.</p>
            <p><strong>Main Parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>Pipe range (mm)</th>
              <th>Capacity (kg/hr)</th>
              <th>Main motor power (kw)</th>
              <th>Total power (kw)</th>
              <th>Main motor power (kw)</th>
            </tr>
            <tr>
              <td>PEX-A32</td>
              <td>16-32</td>
              <td>20</td>
              <td>7.5</td>
              <td>45</td>
              <td>12</td>
            </tr>
            <tr>
              <td>PEX-A50</td>
              <td>32-50</td>
              <td>25</td>
              <td>11</td>
              <td>45</td>
              <td>12</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle2Cat3 }" @click="toggle2Category3()">
      <h2>PPR pipe line</h2> 
      <img src='../assets/images/PPR pipe line.jpg' :class="{ '__expand' : toggle2Cat3 }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat3">
          <div class="product-info">
            <h1>PPR PIPE PRODUCTION LINE</h1>
            <p><strong>Working flow:</strong></p>
            <p>Mixer→ Automatic Charger→ Material dry → Single screw extruder →Marking line extruder(co-extrusion)→Mould→ Vacuum calibration tank → Spraying cooling tank →Ink Printer→  Haul-off machine →Cutter →Stacker</p>
            <p><strong>Application:</strong></p>
            <p>The single wall corrugated pipe are widely used in fields of auto wire, electric thread-passing pipes, circuit of machine tool, protective pipes of lamps and lanterns wire, tubes of air conditioner and washing machine, etc.</p>
            <p><strong>Main technical parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>PPR-32</th>
              <th>PPR-63</th>
              <th>PPR-110</th>
            </tr>
            <tr>
              <td>Specifications of extruder</td>
              <td>SJ65/30</td>
              <td>SJ90/30</td>
              <td>SJ120/28</td>
            </tr>
            <tr>
              <td>Pipe Type(mm)</td>
              <td>φ 16- φ 32</td>
              <td>φ 20- φ 63</td>
              <td>φ 20- φ 110</td>
            </tr>
            <tr>
              <td>Production line speed(m/min)</td>
              <td>≥ 3~10</td>
              <td>≥ 2~6</td>
              <td>≥ 1.2~4</td>
            </tr>
            <tr>
              <td>Air pressure(≥ 0.6MPa)(m3/min)</td>
              <td>0.3</td>
              <td>0.3</td>
              <td>0.5</td>
            </tr>
            <tr>
              <td>Cooling water flow rate(m3/h)</td>
              <td>2</td>
              <td>4</td>
              <td>8</td>
            </tr>
            <tr>
              <td>Total power(kw)</td>
              <td>72</td>
              <td>115</td>
              <td>150</td>
            </tr>
            <tr>
              <td>Dimension(mm</td>
              <td>20000*4000*1700</td>
              <td>26000*4500*1750</td>
              <td>30000*5000*1750</td>
            </tr>
            <tr>
              <td>Weight(kg)</td>
              <td>3500</td>
              <td>4000</td>
              <td>4500</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle2Cat4 }" @click="toggle2Category4()">
      <h2>PVC Fiber Reinforced Hose Line</h2> 
      <img src='../assets/images/PVC Fiber Reinforced Hose Line.jpg' :class="{ '__expand' : toggle2Cat4 }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat4">
          <div class="product-info">
            <h1>PVC FIBER REINFORCED PIPE PRODUCTION LINE</h1>
            <p><strong>Working flow:</strong></p>
            <p>Main extruder→ Die → Braider → Cooling bath → Drying tank → Haul off → Winder → Ink printer → Electric cabinet</p>
            <p><strong>Application:</strong></p>
            <p>This line is designed to produce PVC fiber reinforced hose ,the wall of which is three layers, outer and inner layer are soft PVC hose ,middle layer is Terylene fiber network, which has good chemical and physical property .It is mainly used for the transportation of high pressure or corrosive gas ,and is widely used in the machinery ;coal mine, oil, chemical, agriculture irrigation ,gas and building.</p>
            <p><strong>Main Parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>JDF45</th>
              <th>JDF55</th>
              <th>JDF65</th>
              <th>JDF75</th>
            </tr>
            <tr>
              <td>Extruder</td>
              <td>SJ45/30</td>
              <td>SJ55/30</td>
              <td>SJ65/30</td>
              <td>SJ75/30</td>
            </tr>
            <tr>
              <td>Diameter range (mm)</td>
              <td>6-16mm</td>
              <td>8-25mm</td>
              <td>12-50mm</td>
              <td>20-50mm</td>
            </tr>
            <tr>
              <td>Output(kg/hour)</td>
              <td>20-40</td>
              <td>30-60</td>
              <td>40-80</td>
              <td>60-110</td>
            </tr>
            <tr>
              <td>Installation power(kw)</td>
              <td>35</td>
              <td>42</td>
              <td>50</td>
              <td>65</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle2Cat5 }" @click="toggle2Category5()">
      <h2>PVC reinforced pipe line</h2> 
      <img src='../assets/images/PVC reinforced pipe line.jpg' :class="{ '__expand' : toggle2Cat5 }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat5">
          <div class="product-info">
            <h1>PVC reinforced pipe line</h1>
            <p><strong>Working flow:</strong></p>
            <p>Extruder(2 sets) → forming unit → cooling bath → winder</p>
            <p><strong>Application:</strong></p>
            <p>TPipe formed by soft PVC and rigid PVC spring, strengthen pressure. This pipe is has features as: press resistance, corrosion resistance, anti-bending, good liquidity, etc. It is widely used in fields of industry, agriculture, construction and irrigation, etc.</p>
            <p><strong>Main Parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>SJ45</th>
              <th>SJ65</th>
            </tr>
            <tr>
              <td>Extruder</td>
              <td>SJ45/28</td>
              <td>SJ65/28</td>
            </tr>
            <tr>
              <td>Diameter range (mm)</td>
              <td>13-50mm</td>
              <td>64-200mm</td>
            </tr>
            <tr>
              <td>Output(kg/hour)</td>
              <td>20-40</td>
              <td>40-75</td>
            </tr>
            <tr>
              <td>Installation power(kw)</td>
              <td>35</td>
              <td>50</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle2Cat6 }" @click="toggle2Category6()">
      <h2>PVC, UPVC Pipe Production Line</h2> 
      <img src='../assets/images/PVC UPVC PIPE PRODUCTION LINE.jpg' :class="{ '__expand' : toggle2Cat6 }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat6">
          <div class="product-info">
            <h1>PVC, UPVC Pipe Production Line</h1>
            <p><strong>Application &Advantages:</strong></p>
            <p>1. GF series plastic pipe production line is mainly used in manufacture of the plastic PVC pipes with tube diameters and wall thickness, which are used for water supply and drainage in the field of agriculture and construction.</p>
            <p>2. This line is composed of conical twin-screw extruder, vacuum calibration table, haul-off, cutter, stacker etc.</p>
            <p>3. The extruder and the haul-off adopt the quality AC frequency conversion control device.</p>
            <p>4. The vacuum pump and motor adopt the famous brand.</p>
            <p>5. The haul-off have two-claw, three-claw, four-claw, six-claw.</p>
            <p>6. It may choose the saw blade cutting type or the planet cutting production efficiency.</p>
            <p>7. Our company may equipped the special device for the manufacture of the inner wall spiral coil and core layer blister according to the client’s requirement.</p>
            <p><strong>Main parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Specification</th>
              <th>16-40 Dual</th>
              <th>20-63 Dual</th>
              <th>20-75</th>
              <th>50-250</th>
              <th>250-500</th>
              <th>315-630</th>
            </tr>
            <tr>
              <td>Max. pipe diameter (mm)</td>
              <td>40</td>
              <td>60</td>
              <td>75</td>
              <td>250</td>
              <td>500</td>
              <td>630</td>
            </tr>
            <tr>
              <td>Main conical extruder</td>
              <td>SJSZ51/105</td>
              <td>SJSZ65/132</td>
              <td>SJSZ51/105</td>
              <td>SJZ65/132</td>
              <td>SJSZ80/156</td>
              <td>SJZ92/188</td>
            </tr>
            <tr>
              <td>Max. capacity (KG)</td>
              <td>120</td>
              <td>250</td>
              <td>120</td>
              <td>250</td>
              <td>350</td>
              <td>800</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle2Cat7 }" @click="toggle2Category7()">
      <h2>PU air pipe extrusion line</h2> 
      <img src='../assets/images/PU air pipe extrusion line.jpg' :class="{ '__expand' : toggle2Cat7 }">
        <transition name="expand">
        <div class="category" v-if="toggle2Cat7">
          <div class="product-info">
            <h1>PU air pipe extrusion line</h1>
            <p><strong>Main Component:</strong></p>
            <p>Main extruder - mould - cooling tank- winding machine - Haul off - Winder </p>
            <p><strong>Main Parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>PVC air pipe extrusion line（single layer/double layer</th>
            </tr>
            <tr>
              <td>Main extruder</td>
              <td>Main extruder</td>
            </tr>
            <tr>
              <td>Mould</td>
              <td>φ6.5*10. φ8*12</td>
            </tr>
            <tr>
              <td>Cooling tank</td>
              <td>3m</td>
            </tr>
            <tr>
              <td>Winding machine</td>
              <td>2x12 pc</td>
            </tr>
             <tr>
              <td>Haul off</td>
              <td>0~18 m/min</td>
            </tr>
             <tr>
              <td>Winder</td>
              <td> </td>
            </tr>
             <tr>
              <td>Control cabinet</td>
              <td>ABB invertor</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
    </div>
  </div>

  <div class="prod">
    <div class="headline">
      <h1>Plastic Auxiliary Machines</h1>
    </div>
    <div class="__icons">
      <div class="__icon" :class="{ '__expand' : toggle3Cat }" @click="toggle3Category()">
      <h2>pipe winder machine</h2> 
      <img src='../assets/images/pipe winder machine.jpg' :class="{ '__expand' : toggle3Cat }">
        <transition name="expand">
        <div class="category" v-if="toggle3Cat">
          <div class="product-info">
            <h1>pipe winder machine</h1>
            <p><strong>SINGLE AND  DOUBLE WINDER</strong></p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>DS32</th>
              <th>DS63</th>
              <th>DS110</th>
            </tr>
            <tr>
              <td>Suitable pipe diameter</td>
              <td>16-32</td>
              <td>32-63</td>
              <td>63-110</td>
            </tr>
            <tr>
              <td>Winding speed</td>
              <td>Automatic adjusting according to pipe extrusion speed</td>
            </tr>
            <tr>
              <td>Winding inner diameter</td>
              <td>Adjustable</td>
            </tr>
            <tr>
              <td>Winding width of roll</td>
              <td>Adjustable</td>
            </tr>
            <tr>
              <td>Winding arrangement</td>
              <td>Automatic displacer</td>
            </tr>
            <tr>
              <td>Discharge of roll</td>
              <td>Pneumatic drive</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggleCat }" @click="toggle3Category2()">
      <h2>Conical twin screw extruder</h2> 
      <img src='../assets/images/Conical twin screw extruder.jpg' :class="{ '__expand' : toggle3Cat2 }">
        <transition name="expand">
        <div class="category" v-if="toggle3Cat2">
          <div class="product-info">
            <h1>SJZ CONICAL TWIN SCREW EXTRUDER</h1>
            <p>SJZ series conical double screw extruder especially used for extrusion PVC powder, it has advantages as good mixing, large output, working steady , long service life time etc. equipped with series mold and auxiliary machine, it can produce various PVC pipes, profiles, sheets, plates, bars and it also can be used for pelletizing.</p>
            <p><strong>Main Parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Item</th>
              <th>SJZ-51/105</th>
              <th>SJZ-55/110</th>
              <th>SJZ-65/132</th>
              <th>SJZ-80/156</th>
              <th>SJZ-80/156</th>
            </tr>
            <tr>
              <td>Diameter of screw (mm)</td>
              <td>51/105</td>
              <td>55/110</td>
              <td>65/132</td>
              <td>80/156</td>
              <td>92/188</td>
            </tr>
            <tr>
              <td>Number of screw</td>
              <td>2</td>
              <td>2</td>
              <td>2</td>
              <td>2</td>
              <td>2</td>
            </tr>
            <tr>
              <td>Rotation direction of screw</td>
              <td>Counter rotation outward</td>
            </tr>
            <tr>
              <td>Screw rotation speed (rpm)</td>
              <td>1-37</td>
              <td>1-30</td>
              <td>1-34.7</td>
              <td>1-36.9</td>
              <td>1-32.9</td>
            </tr>
            <tr>
              <td>Effective length of screw(mm)</td>
              <td>1065</td>
              <td>1200</td>
              <td>1440</td>
              <td>1800</td>
              <td>2500</td>
            </tr>
            <tr>
              <td>Barrel heating power(kw)</td>
              <td>10</td>
              <td>18</td>
              <td>24</td>
              <td>36</td>
              <td>86.8</td>
            </tr>
            <tr>
              <td>Production capacity(kg/hr)</td>
              <td>135(MAX)</td>
              <td>80-140(MAX)</td>
              <td>250(MAX)</td>
              <td>320-450(MAX)</td>
              <td>500-600(MAX)</td>
            </tr>
            <tr>
              <td>Canter height(mm)</td>
              <td>1000</td>
              <td>1000</td>
              <td>1000</td>
              <td>1000</td>
              <td>1000</td>
            </tr>
            <tr>
              <td>Net weight (kg)</td>
              <td>2500</td>
              <td>3500</td>
              <td>4000</td>
              <td>5000</td>
              <td>10000</td>
            </tr>
            <tr>
              <td>Dimension (mm)</td>
              <td>3235*1100*2157</td>
              <td>3620*1050*2157</td>
              <td>4235*1520*2450</td>
              <td>4750*1550*2460</td>
              <td>6725*1550*2841</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle3Cat3 }" @click="toggle3Category3()">
      <h2>PVC Pipe Belling Machine</h2> 
      <img src='../assets/images/PVC PIPE BELLING MACHINE.jpg' :class="{ '__expand' : toggle3Cat3 }">
        <transition name="expand">
        <div class="category" v-if="toggle3Cat3">
          <div class="product-info">
            <h1>PVC Pipe Belling Machine</h1>
            <p><strong>Specifications:</strong></p>
            <p>1.  Automatic pvc pipe belling machine</p>
            <p>2.  Pipe diameter (mm):16~75mm, 50~160mm, 50~250mm, 110~315mm, 315~630mm</p>
            <p><strong>Application:</strong></p>
            <p>SGK series fully automatic plastic belling machine is suitable for the PVC pipe belling .It bell R-type and Z-type .The belling range 50-630 mm.</p>
            <p><strong>Features:</strong></p>
            <p>Shaping way adopts rising in the mould and rises and increasing the barometric pressure out of the mould to make it stereotypic. Many years experience and exported to many countries of all the world</p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>SGK75</th>
              <th>SGK160</th>
              <th>SGK250</th>
              <th>SGK315</th>
              <th>SGK630</th>
            </tr>
            <tr>
              <td>Pipe scope(mm)</td>
              <td>16~75</td>
              <td>50~160</td>
              <td>50~250</td>
              <td>110~315</td>
              <td>315~630</td>
            </tr>
            <tr>
              <td>Total power(kw)</td>
              <td>15</td>
              <td>18</td>
              <td>18</td>
              <td>20</td>
              <td>32</td>
            </tr>
            <tr>
              <td>Out dimension (mm)</td>
              <td>7460*1950*1900</td>
              <td>6900*1420*2000</td>
              <td>7300*1660*1920</td>
              <td>8200*1750*1850</td>
              <td>8420*2970*2650</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle3Cat4 }" @click="toggle3Category4()">
      <h2>Mixer machine</h2> 
      <img src='../assets/images/mixer machine.jpg' :class="{ '__expand' : toggle3Cat4 }">
        <transition name="expand">
        <div class="category" v-if="toggle3Cat4">
          <div class="product-info">
            <h1>SRL MIXER MACHINE</h1>
            <p>SRL-Series heating-cooling mixing machine unit is widely used in process of mixing, drying, coloring and cooling of variously plastic powder, liquid, granules, rubber, dyestuffs, foodstuffs, chemicals, CaCo3, etc</p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>SRL-Z100/200</th>
              <th>SRL-Z200/500</th>
              <th>SRL-Z300/600</th>
              <th>SRL-Z500/1000</th>
              <th>SRL-Z800/1600</th>
            </tr>
            <tr>
              <td>Total volume</td>
              <td>100/200</td>
              <td>200/500</td>
              <td>300/600</td>
              <td>500/1000</td>
              <td>800/1600</td>
            </tr>
           <tr>
              <td>Volume</td>
              <td>75/160</td>
              <td>150/320</td>
              <td>225/400</td>
              <td>375/650</td>
              <td>600/1050</td>
            </tr>
            <tr>
              <td>Rotation speed</td>
              <td>650/130/180</td>
              <td>475/950/130</td>
              <td>475/950/60</td>
              <td>430/860/60</td>
              <td>370/740/50</td>
            </tr>
            <tr>
              <td>Method</td>
              <td>self friction water cooling</td>
              <td>self friction water cooling</td>
              <td>self friction water cooling</td>
              <td>self friction water cooling</td>
              <td>self friction water cooling</td>
            </tr>
            <tr>
              <td>Mixing time</td>
              <td>6-10</td>
              <td>6-10</td>
              <td>6-10</td>
              <td>6-10</td>
              <td>8-12</td>
            </tr>
            <tr>
              <td>Motor power</td>
              <td>14/22/7.5</td>
              <td>30/42/7.5</td>
              <td>40/55/11</td>
              <td>55/75/11</td>
              <td>60/90</td>
            </tr>
            <tr>
              <td>Size</td>
              <td>3780×1870×2250</td>
              <td>4580×2240×2470</td>
              <td>4580×2240×2470</td>
              <td>4600×3000×4050</td>
              <td>4850×3860×6550</td>
            </tr>
            <tr>
              <td>Weight</td>
              <td>3200</td>
              <td>3400</td>
              <td>4000</td>
              <td>5800</td>
              <td>8700</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>
      <div class="__icon" :class="{ '__expand' : toggle3Cat5 }" @click="toggle3Category5()">
      <h2>Plastic pulverizer</h2>
      <img src='../assets/images/plastic pulverizer.jpg' :class="{ '__expand' : toggle3Cat5 }">
      <transition name="expand">
        <div class="category" v-if="toggle3Cat5">
          <div class="product-info">
            <h1>Plastic pulverizer</h1>
            <p><strong>Advantages of SMW & SMF series disc type plastic pulverizer machine (plastic milling machine)</strong></p>
            <p>1. Safe and simple adjustment of cutting gap</p>
            <p>2. Low energy consumption and high throughput</p>
            <p>3. Innovative and energy efficient design</p>
            <p>4. Easy to maintain and control</p>
            <p>5. Wide range of accessories</p>
            <p>6. Regrinding coarse powder automatically</p>
            <p>7. Dual cooling system</p>
            <h4>SMW series pulverizer machine</h4>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>SMW-500</th>
              <th>SMW-600</th>
              <th>SMW-800</th>
            </tr>
            <tr>
              <td>Motor power (kw)</td>
              <td>37kw</td>
              <td>55kw</td>
              <td>75kw</td>
            </tr>
            <tr>
              <td>Blow power (kw)</td>
              <td>3kw</td>
              <td>5.5kw</td>
              <td>11kw</td>
            </tr>
            <tr>
              <td>Voltage (customize)</td>
              <td>380V, 50Hz</td>
              <td>380V, 50Hz</td>
              <td>380V, 50Hz</td>
            </tr>
            <tr>
              <td>Total power</td>
              <td>41kw</td>
              <td>52kw</td>
              <td>90.5kw</td>
            </tr>
            <tr>
              <td>Blade Dia.</td>
              <td>500mm</td>
              <td>600mm</td>
              <td>800mm</td>
            </tr>
            <tr>
              <td>Feeding size</td>
              <td>Below 10mm</td>
              <td>Below 10mm</td>
              <td>Below 10mm</td>
            </tr>
            <tr>
              <td>Output size</td>
              <td>40-80mesh</td>
              <td>40-80mesh</td>
              <td>40-80mesh</td>
            </tr>
            <tr>
              <td>Vibration model</td>
              <td>ZDS-800</td>
              <td>ZDS-1000</td>
              <td>ZDS-1200</td>
            </tr>
            <tr>
              <td>Capacity</td>
              <td>200-300kg/h</td>
              <td>300-500kg/h</td>
              <td>500-600kg/h</td>
            </tr>
            <tr>
              <td>Machine size(mm)</td>
              <td>2500*2000*3000mm</td>
              <td>3200*2600*3200mm</td>
              <td>3500*2400*4000mm</td>
            </tr>
          </table>
          <h4>SMF series pulverizer machine</h4>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>SMF-400</th>
              <th>SMF-610</th>
              <th>SMF-800</th>
            </tr>
            <tr>
              <td>Blade disc size</td>
              <td>400mm</td>
              <td>610mm</td>
              <td>800mm</td>
            </tr>
            <tr>
              <td>Blade disc quantity</td>
              <td>2 pieces</td>
              <td>2 pieces</td>
              <td>2 pieces</td>
            </tr>
            <tr>
              <td>Shaft rotary speed</td>
              <td>4500 rpm</td>
              <td>4200 rpm</td>
              <td>3700 rpm</td>
            </tr>
            <tr>
              <td>Main motor power</td>
              <td>30kw</td>
              <td>45kw</td>
              <td>55kw</td>
            </tr>
            <tr>
              <td>Blower power</td>
              <td>3kw</td>
              <td>5.5kw</td>
              <td>7.5kw</td>
            </tr>
            <tr>
              <td>Flow valve power</td>
              <td>0.75kw</td>
              <td>0.75kw</td>
              <td>1.1kw</td>
            </tr>
            <tr>
              <td>Powder size</td>
              <td>10-100mesh</td>
              <td>10-100mesh</td>
              <td>10-100mesh</td>
            </tr>
            <tr>
              <td>Cooling method</td>
              <td>Air cooling & water cooling</td>
              <td>Air cooling & water cooling</td>
              <td>Air cooling & water cooling</td>
            </tr>
            <tr>
              <td>Capacity</td>
              <td>150kg/h (PVC)<br/>80kg/h (PP)<br/>20kg/h (PE)</td>
              <td>250kg/h (PVC)<br/>160kg/h (PP)<br/>350kg/h (PE)</td>
              <td>350-400kg/h (PVC)<br/>200-250kg/h (PP)<br/>500kg/h (PE)</td>
            </tr>
            <tr>
              <td>Machine size</td>
              <td>2500*2000*3000mm</td>
              <td>2800*2300*3000mm</td>
              <td>3200*2800*3200mm</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>

      <div class="__icon" :class="{ '__expand' : toggle3Cat6 }" @click="toggle3Category6()">
      <h2>PVC pelletizing Line</h2> 
      <img src='../assets/images/PVC PELLETIZING LINE.jpg' :class="{ '__expand' : toggle3Cat6 }">
        <transition name="expand">
        <div class="category" v-if="toggle3Cat6">
          <div class="product-info">
            <h1>PVC PELLETIZING LINE</h1>
            <p><strong>Features and Application:</strong></p>
            <p>The machine mainly produces PVC granules by hot cutting. The equipment is advanced, it has characteristic of strong universal and high output.</p>
            <p><strong>Main Parameters:</strong></p>
            <table class="prod-table">
            <tr>
              <th>Model</th>
              <th>SJZ45</th>
              <th>SJZ65</th>
              <th>SJZ80</th>
            </tr>
            <tr>
              <td>Power</td>
              <td>15KW</td>
              <td>37KW</td>
              <td>55KW</td>
            </tr>
            <tr>
              <td>Production capacity</td>
              <td>120kg/hr</td>
              <td>280kg/hr</td>
              <td>350kg/hr</td>
            </tr>
            <tr>
              <td>Granule specification</td>
              <td>3mm</td>
              <td>3mm</td>
              <td>3mm</td>
            </tr>
            <tr>
              <td>Total length of production line</td>
              <td>12m</td>
              <td>12m</td>
              <td>15m</td>
            </tr>
          </table>
          </div>
        </div>
      </transition>
      </div>

    </div>
  </div>

  </div>
</template>

<script>
/* eslint-disable */

export default {

  mounted() {
    window.scrollTo(0,0);
  },

  // watch: {

  //     handler(val) {
  //       let allIcons = document.getElementsByClassName("__icon");
  //       let i;

  //     for (i = 0; i < this.allIcons.length; i++) {
  //       this.allIcons[i].addEventListener("click", function() {
  //         this.classList.toggle("active");
  //         var content = this.nextElementSibling;
  //         console.log(content);
  //         if (content.style.display === "block") {
  //           content.style.display = "none";
  //         } else {
  //           content.style.display = "block";
  //         }
  //       });
  //     }
  //     },
  //     deep: true
  // },

  data() {
    return {
      toggleCat: false,
      toggleCat2: false,
      toggleCat3: false,
      toggleCat4: false,
      toggleCat5: false,
      toggleCat6: false,
      toggleCat7: false,

      toggle2Cat: false,
      toggle2Cat2: false,
      toggle2Cat3: false,
      toggle2Cat4: false,
      toggle2Cat5: false,
      toggle2Cat6: false,
      toggle2Cat7: false,

      toggle3Cat: false,
      toggle3Cat2: false,
      toggle3Cat3: false,
      toggle3Cat4: false,
      toggle3Cat5: false,
      toggle3Cat6: false,
    }
  }, 
  methods: {
    toggleCategory(){
      this.toggleCat = !this.toggleCat;
      window.scrollBy(0,150);
    },
    toggleCategory2(){
      this.toggleCat2 = !this.toggleCat2;
      window.scrollBy(0,150);
    },
    toggleCategory3(){
      this.toggleCat3 = !this.toggleCat3;
      window.scrollBy(0,150);
    },
    toggleCategory4(){
      this.toggleCat4 = !this.toggleCat4;
      window.scrollBy(0,150);
    },
    toggleCategory5(){
      this.toggleCat5 = !this.toggleCat5;
      window.scrollBy(0,150);
    },
    toggleCategory6(){
      this.toggleCat6 = !this.toggleCat6;
      window.scrollBy(0,150);
    },
    toggleCategory7(){
      this.toggleCat7 = !this.toggleCat7;
      window.scrollBy(0,150);
    },

    toggle2Category(){
      this.toggle2Cat = !this.toggle2Cat;
      window.scrollBy(0,150);
    },
    toggle2Category2(){
      this.toggle2Cat2 = !this.toggle2Cat2;
      window.scrollBy(0,150);
    },
    toggle2Category3(){
      this.toggle2Cat3 = !this.toggle2Cat3;
      window.scrollBy(0,150);
    },
    toggle2Category4(){
      this.toggle2Cat4 = !this.toggle2Cat4;
      window.scrollBy(0,150);
    },
    toggle2Category5(){
      this.toggle2Cat5 = !this.toggle2Cat5;
      window.scrollBy(0,150);
    },
    toggle2Category6(){
      this.toggle2Cat6 = !this.toggle2Cat6;
      window.scrollBy(0,150);
    },
    toggle2Category7(){
      this.toggle2Cat7 = !this.toggle2Cat7;
      window.scrollBy(0,150);
    },

    toggle3Category(){
      this.toggle3Cat = !this.toggle3Cat;
      window.scrollBy(0,150);
    },
    toggle3Category2(){
      this.toggle3Cat2 = !this.toggle3Cat2;
      window.scrollBy(0,150);
    },
    toggle3Category3(){
      this.toggle3Cat3 = !this.toggle3Cat3;
      window.scrollBy(0,150);
    },
    toggle3Category4(){
      this.toggle3Cat4 = !this.toggle3Cat4;
      window.scrollBy(0,150);
    },
    toggle3Category5(){
      this.toggle3Cat5 = !this.toggle3Cat5;
      window.scrollBy(0,150);
    },
    toggle3Category6(){
      this.toggle3Cat6 = !this.toggle3Cat6;
      window.scrollBy(0,150);
    },
  }
}
</script>

<style>

</style>
