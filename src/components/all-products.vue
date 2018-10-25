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
            <h2>KE-180 Base Material Edge Trimming Film Recycling Unit</h2>
            <p><strong>Working Priciple:</strong></p>
            <p>The rim charges of membrane get into pressing unit through feeding unit. After solid pressing, the rim charges are transmitted into cutting unit for granule cutting.</p>
            <p><strong>Application:</strong></p>
            <p>CPE, PE, CPP, PO, PP, EVA, BOPA, POF, LLDPE, TPE, and nonwoven, etc.</p>
            <table id="customers">
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
            <h2>PE PP film washing line</h2>
            <p><strong>Working Flow:</strong></p>
            <p>Belt conveyor * 2 → Crusher * 2 → Screw conveyor* 2 → Floating washer → High speed friction machine → Screw conveyor →  Horizontal dewatering machine → Drying pipe system → Transition storage  → Drying pipe system →Storage hopper → Control cabinet</p>
            <table id="customers">
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
            <h2>HDPE, PP bottle, container, crate, barrel washing line</h2>
            <p><strong>Working Flow:</strong></p>
            <p>Belt conveyor → Crusher  → Screw conveyor → （Hot）Floating washer → Screw conveyor →  Vertical dewatering machine → Drying pipe system → Zig Zag air classification system →Storage hopper → Control cabinet</p>
            <table id="customers">
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
            <h2>Pet bottle washing line</h2>
            <p><strong>Working Flow:</strong></p>
            <p>Belt conveyor → Roll separator → Belt conveyor → Mechanical label remover → Manual separating table → Metal detector →Belt conveyor → Crusher → Screw conveyor → High speed friction machine → Screw conveyor → Floating washer → Screw conveyor → Hot washer → Screw conveyor → Floating washer → Screw conveyor → Vertical dewatering machine → Drying pipe system → Zig zag air classification system → Storage hopper → Control cabinet</p>
            <h4>Estimated Plant Parameters:</h4>
            <table id="customers">
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
          </div>
        </div>
      </transition>
      </div>
    </div>
  </div>

  <div class="why">
    <div class="headline">
      <h1>Plastic Pipe/profile Extrusion Line</h1>
    </div>
    <div class="__icons">
      <div class="__icon"  >
          
      <img src='../assets/images/Film shredder.jpg' style="width:100%">

        <h2>Regrinds</h2>
        <p style="text-align:center">
            High quality plastic regrinds suitable for all your needs.
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Granulator.jpg' style="width:100%">

        <h2>Separation</h2>
        <p style="text-align:center">
            State of the art separation technology – even by colour! 
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Aglomorator.jpg' style="width:100%">

        <h2>Compounds</h2>
        <p style="text-align:center">
           Superior polymer compounds made to your specifications. 
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Single shaft lump shredder.jpg' style="width:100%">

        <h2>We Buy Plastic Scrap</h2>
        <p style="text-align:center">
           We recycle scrap including manufacturers & packaging waste. 
        </p>
      </div>
    </div>
  </div>

  <div class="why">
    <div class="headline">
      <h1>Plastic Auxiliary Machines</h1>
    </div>
    <div class="__icons">
      <div class="__icon"  >
          
      <img src='../assets/images/Film shredder.jpg' style="width:100%">

        <h2>Regrinds</h2>
        <p style="text-align:center">
            High quality plastic regrinds suitable for all your needs.
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Granulator.jpg' style="width:100%">

        <h2>Separation</h2>
        <p style="text-align:center">
            State of the art separation technology – even by colour! 
        </p>
      </div>
      <div class="__icon" >
          
      <img src='../assets/images/Aglomorator.jpg' style="width:100%">

        <h2>Compounds</h2>
        <p style="text-align:center">
           Superior polymer compounds made to your specifications. 
        </p>
      </div>
      <div class="__icon">
          
      <img src='../assets/images/Single shaft lump shredder.jpg' style="width:100%">

        <h2>We Buy Plastic Scrap</h2>
        <p style="text-align:center">
           We recycle scrap including manufacturers & packaging waste. 
        </p>
      </div>
    </div>
  </div>

  </div>
</template>

<script>
/* eslint-disable */

export default {

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
    }
  }
}
</script>

<style>

</style>
