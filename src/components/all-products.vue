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
      <img src='../assets/images/KE-180 Base Material Edge Trimming Film Recycling Unit.jpg' :class="{ '__expand' : toggleCat }">
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
      <img src='../assets/images/PEPP-film-washing.jpg' :class="{ '__expand' : toggleCat2 }">
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
    </div>
  </div>

  <div class="prod">
    <div class="headline">
      <h1>Plastic Auxiliary Machines</h1>
    </div>
    <div class="__icons">
      <div class="__icon" :class="{ '__expand' : toggleCat }" @click="toggleCategory()">
      <h2>KE-180 Base Material Edge Trimming Film Recycling Unit</h2> 
      <img src='../assets/images/KE-180 Base Material Edge Trimming Film Recycling Unit.jpg' :class="{ '__expand' : toggleCat }">
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
      <div class="__icon" :class="{ '__expand' : toggleCat }" @click="toggleCategory()">
      <h2>KE-180 Base Material Edge Trimming Film Recycling Unit</h2> 
      <img src='../assets/images/KE-180 Base Material Edge Trimming Film Recycling Unit.jpg' :class="{ '__expand' : toggleCat }">
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
      <div class="__icon" :class="{ '__expand' : toggleCat }" @click="toggleCategory()">
      <h2>KE-180 Base Material Edge Trimming Film Recycling Unit</h2> 
      <img src='../assets/images/KE-180 Base Material Edge Trimming Film Recycling Unit.jpg' :class="{ '__expand' : toggleCat }">
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
      <div class="__icon" :class="{ '__expand' : toggleCat }" @click="toggleCategory()">
      <h2>KE-180 Base Material Edge Trimming Film Recycling Unit</h2> 
      <img src='../assets/images/KE-180 Base Material Edge Trimming Film Recycling Unit.jpg' :class="{ '__expand' : toggleCat }">
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
  }
}
</script>

<style>

</style>
