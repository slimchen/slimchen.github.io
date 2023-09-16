<template>
  <div class="home">
    <h1 class="title">
      Search Used Car Prices
    </h1>
    <div class="dropdowns-container">
      <div class="dropdowns-container1">
        <!-- make -->
        <el-dropdown>
          <el-button type="primary">
            Make<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Volkswagen</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Family -->
        <el-dropdown>
          <el-button type="primary">
            Family<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Caddy</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Year -->
        <el-dropdown>
          <el-button type="primary">
            Year<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>2003 | 2004</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Badges -->
        <el-dropdown>
          <el-button type="primary">
            Badges<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Blank</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Body Type -->
        <el-dropdown>
          <el-button type="primary">
            Body Type<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Sedan</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Body Type Config -->
        <el-dropdown>
          <el-button type="primary">
            Body Type Config<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Blank</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Fuel Type -->
        <el-dropdown>
          <el-button type="primary">
            Fuel Type<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Petrol</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
      </div>
      <div class="dropdowns-container2">
        <!-- Transmission -->
        <el-dropdown>
          <el-button type="primary">
            Transmission<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Automatic</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Engine -->
        <el-dropdown>
          <el-button type="primary">
            Engine<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>2.0</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Cylinders -->
        <el-dropdown>
          <el-button type="primary">
            Cylinders<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>4</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Division -->
        <el-dropdown>
          <el-button type="primary">
            Division<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Motor Vehicles</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Drive -->
        <el-dropdown>
          <el-button type="primary">
            Drive<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Front Wheel Drive</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Seat -->
        <el-dropdown>
          <el-button type="primary">
            Seat<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>5</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Doors -->
        <el-dropdown>
          <el-button type="primary">
            Doors<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>4</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
      </div>
      <div class="dropdowns-container3">
        <!-- Odometer -->
        <el-dropdown>
          <el-button type="primary">
            Odometer<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>80,000-90,000 km</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- States -->
        <el-dropdown>
          <el-button type="primary">
            States<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>VIC</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Sale Category -->
        <el-dropdown>
          <el-button type="primary">
            Sale Category<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Dealership</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Sale Date -->
        <el-dropdown>
          <el-button type="primary">
            Sale Date<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Last 7 days</el-dropdown-item>
            <el-dropdown-item>Last 30 days</el-dropdown-item>
            <el-dropdown-item>Last 90 days</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Sort -->
        <el-dropdown>
          <el-button type="primary">
            Sort<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>Sold Date</el-dropdown-item>
            <el-dropdown-item>Age</el-dropdown-item>
            <el-dropdown-item>Odometer</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
        <!-- Order By -->
        <el-dropdown>
          <el-button type="primary">
            Order By<i class="el-icon-arrow-down el-icon--right"></i>
          </el-button>
          <el-dropdown-menu slot="dropdown">
            <el-dropdown-item>ASC</el-dropdown-item>
            <el-dropdown-item>DESC</el-dropdown-item>
          </el-dropdown-menu>
        </el-dropdown>
      </div>
    </div>
    <div class="serch-bar">
      <el-input type="textarea" autosize placeholder="Please input" v-model="textarea1" style="width: 400px; margin-right: 10px;">
      </el-input>
      <el-button type="success">Apply Filter</el-button>
      <el-button type="success">Clear Filter</el-button>
      <el-button type="danger">Subscibe to Generate Summary Report</el-button>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'HomeView',
}
</script>

<style>
/* Title */
.title {
  margin-right: 20px;
}

/* Style for the container to display dropdowns */
.dropdowns-container {
  display: flex;
  flex-direction: column;
  align-items: center;
}

.dropdowns-container1 {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;

}

.dropdowns-container2 {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}

.dropdowns-container3 {
  display: flex;
  gap: 10px;
  margin-bottom: 10px;
}

.dropdown-item {
  width: 200px;
}
/* Style for the container to search bar widgets */
.serch-bar {
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 550px;
}
</style>