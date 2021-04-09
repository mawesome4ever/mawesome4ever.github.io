<html>
<!-- File Search For:
        -PartList   : HTML list of all the parts
        -ActualParts: HTML details of all the parts
        -SearchBar  : Script for search bar functionality
    -->

<head>
    <style>
            body {
        background: #3B3B3B;
      }
      h1 {
        display:none;
      }
/* When the screen is less than 600px wide, stack the links and the search field vertically instead of horizontally 
      @media screen and (max-width: 600px) {*/
        .topnav a, .topnav input[type=search] {
          float: none;
          display: block;
          text-align: left;
          width: 100%;
          margin: 0;
          padding: 14px;
          color:#fff;
          background-color: #3B3B3B;
        }
        .topnav input[type=search] {
          border: 1px solid #fff;
        }
      
      #PartItem {
        border-radius: 25px;
        color: #ffffff;
        width: 95%;
        position:center;
        display: block;
        border: 1px solid #fff;
        margin: 10px;
        text-align: center;
      }
      #PartItem figure  {
        text-align: left;
        border: 0px;
        background-color: #3B3B3B;
        position:center;
      }
      #PartItem table  {
        text-align: left;
        width:100%;
        position:inherit;
        padding-left: 3%;
        padding-right: 3%;
        padding-bottom: 1%;
        background-color: #3B3B3B;
      }
      .has-subtle-pale-blue-background-color.has-fixed-layout.has-background{
        width: 100%;
        background-color: #3B3B3B;
      }
      tr {
        background-color:#3B3B3B;
      }
      table {
        background-color:#3B3B3B;
      }
      td {
        background-color:#3B3B3B;
        color: #fff;
      }
      /* unvisited link */
      a:link {
        color: #3D97D4;
      }

      /* visited link */
      a:visited {
        color: green;
      }

      /* mouse over link */
      a:hover {
        color: hotpink;
      }

      /* selected link */
      a:active {
        color: #3D97D4;
      }
     </style>
</head>

<body>
    <p> There are a total of 279 Parts </p>
    <div class="topnav"> <input id="TextBox" placeholder="Search.." onsearch="LookUp()" type="search"></div>
    <!-- PartList -->
    <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background" style="border:0px">
        <tbody>
            <tr>
                <td>
                    <ul>
                        <li class="part"><a href="#Aerogel">Aerogel</a></li>
                        <li class="part"><a href="#AirSupply">AirSupply</a></li>
                        <li class="part"><a href="#AlienCore">AlienCore</a></li>
                        <li class="part"><a href="#Aluminum">Aluminum</a></li>
                        <li class="part"><a href="#Anchor">Anchor</a></li>
                        <li class="part"><a href="#Antenna">Antenna</a></li>
                        <li class="part"><a href="#Apparel">Apparel</a></li>
                        <li class="part"><a href="#Aquarium">Aquarium</a></li>
                        <li class="part"><a href="#Artillery">Artillery</a></li>
                        <li class="part"><a href="#Asphalt">Asphalt</a></li>
                        <li class="part"><a href="#Assembler">Assembler</a></li>
                        <li class="part"><a href="#AutomaticLaser">AutomaticLaser</a></li>
                        <li class="part"><a href="#BallTemplate">BallTemplate</a></li>
                        <li class="part"><a href="#BallastTank">BallastTank</a></li>
                        <li class="part"><a href="#Balloon">Balloon</a></li>
                        <li class="part"><a href="#BasePart">BasePart</a></li>
                        <li class="part"><a href="#Battery">Battery</a></li>
                        <li class="part"><a href="#Beacon">Beacon</a></li>
                        <li class="part"><a href="#Beaker">Beaker</a></li>
                        <li class="part"><a href="#BeamRifle">BeamRifle</a></li>
                        <li class="part"><a href="#Beryllium">Beryllium</a></li>
                        <li class="part"><a href="#Bin">Bin</a></li>
                        <li class="part"><a href="#BlackBox">BlackBox</a></li>
                        <li class="part"><a href="#BladeTemplate">BladeTemplate</a></li>
                        <li class="part"><a href="#BlastingCap">BlastingCap</a></li>
                        <li class="part"><a href="#Boiler">Boiler</a></li>
                        <li class="part"><a href="#Boombox">Boombox</a></li>
                        <li class="part"><a href="#Brick">Brick</a></li>
                        <li class="part"><a href="#BurnerGenerator">BurnerGenerator</a></li>
                        <li class="part"><a href="#BurstLaser">BurstLaser</a></li>
                        <li class="part"><a href="#Button">Button</a></li>
                        <li class="part"><a href="#Camera">Camera</a></li>
                        <li class="part"><a href="#CameraEvent">CameraEvent</a></li>
                        <li class="part"><a href="#Cannon">Cannon</a></li>
                        <li class="part"><a href="#Cement">Cement</a></li>
                        <li class="part"><a href="#Charcoal">Charcoal</a></li>
                        <li class="part"><a href="#ChemicalSynthiser">ChemicalSynthiser</a></li>
                        <li class="part"><a href="#Chip">Chip</a></li>
                        <li class="part"><a href="#Chute">Chute</a></li>
                        <li class="part"><a href="#Claymore">Claymore</a></li>
                        <li class="part"><a href="#Cleat">Cleat</a></li>
                        <li class="part"><a href="#CloningBay">CloningBay</a></li>
                        <li class="part"><a href="#Cloth">Cloth</a></li>
                        <li class="part"><a href="#Coal">Coal</a></li>
                        <li class="part"><a href="#CombustionTurbine">CombustionTurbine</a></li>
                        <li class="part"><a href="#Constructor">Constructor</a></li>
                        <li class="part"><a href="#Container">Container</a></li>
                        <li class="part"><a href="#Controller">Controller</a></li>
                        <li class="part"><a href="#ConveyorBelt">ConveyorBelt</a></li>
                        <li class="part"><a href="#Cooler">Cooler</a></li>
                        <li class="part"><a href="#Copper">Copper</a></li>
                        <li class="part"><a href="#CornerRoundTemplate">CornerRoundTemplate</a></li>
                        <li class="part"><a href="#CornerRoundTemplate2">CornerRoundTemplate2</a></li>
                        <li class="part"><a href="#CornerTemplate">CornerTemplate</a></li>
                        <li class="part"><a href="#CornerTetraTemplate">CornerTetraTemplate</a></li>
                        <li class="part"><a href="#Coupler">Coupler</a></li>
                        <li class="part"><a href="#CrossBow">CrossBow</a></li>
                        <li class="part"><a href="#CrudeWing">CrudeWing</a></li>
                        <li class="part"><a href="#CylinderTemplate">CylinderTemplate</a></li>
                        <li class="part"><a href="#DarkConverter">DarkConverter</a></li>
                        <li class="part"><a href="#DarkMatter">DarkMatter</a></li>
                        <li class="part"><a href="#DarkReactor">DarkReactor</a></li>
                        <li class="part"><a href="#DataStoreService">DataStoreService</a></li>
                        <li class="part"><a href="#Decoupler">Decoupler</a></li>
                        <li class="part"><a href="#DelayWire">DelayWire</a></li>
                        <li class="part"><a href="#DeleteSwitch">DeleteSwitch</a></li>
                        <li class="part"><a href="#DevBattery">DevBattery</a></li>
                        <li class="part"><a href="#DevGenerator">DevGenerator</a></li>
                        <li class="part"><a href="#Diamond">Diamond</a></li>
                        <li class="part"><a href="#Disk">Disk</a></li>
                    </ul>
                </td>
                <td>
                    <ul>
                        <li class="part"><a href="#Dispenser">Dispenser</a></li>
                        <li class="part"><a href="#DoorTemplate">DoorTemplate</a></li>
                        <li class="part"><a href="#DriveBox">DriveBox</a></li>
                        <li class="part"><a href="#Egg">Egg</a></li>
                        <li class="part"><a href="#ElectricFence">ElectricFence</a></li>
                        <li class="part"><a href="#Electromagnet">Electromagnet</a></li>
                        <li class="part"><a href="#EnergyBomb">EnergyBomb</a></li>
                        <li class="part"><a href="#EnergyGun">EnergyGun</a></li>
                        <li class="part"><a href="#EnergyShield">EnergyShield</a></li>
                        <li class="part"><a href="#EnergySword">EnergySword</a></li>
                        <li class="part"><a href="#Engine">Engine</a></li>
                        <li class="part"><a href="#EthernetCable">EthernetCable</a></li>
                        <li class="part"><a href="#ExoticMatter">ExoticMatter</a></li>
                        <li class="part"><a href="#Explosive">Explosive</a></li>
                        <li class="part"><a href="#Extractor">Extractor</a></li>
                        <li class="part"><a href="#FactionSpawn">FactionSpawn</a></li>
                        <li class="part"><a href="#Faucet">Faucet</a></li>
                        <li class="part"><a href="#Fence">Fence</a></li>
                        <li class="part"><a href="#Filter">Filter</a></li>
                        <li class="part"><a href="#FingerprintSensor">FingerprintSensor</a></li>
                        <li class="part"><a href="#FireWood">FireWood</a></li>
                        <li class="part"><a href="#Fireworks">Fireworks</a></li>
                        <li class="part"><a href="#Flamethrower">Flamethrower</a></li>
                        <li class="part"><a href="#Flashlight">Flashlight</a></li>
                        <li class="part"><a href="#Flint">Flint</a></li>
                        <li class="part"><a href="#FloatDevice">FloatDevice</a></li>
                        <li class="part"><a href="#FluidProjector">FluidProjector</a></li>
                        <li class="part"><a href="#Food">Food</a></li>
                        <li class="part"><a href="#Framewire">Framewire</a></li>
                        <li class="part"><a href="#Freezer">Freezer</a></li>
                        <li class="part"><a href="#GasTank">GasTank</a></li>
                        <li class="part"><a href="#Gasoline">Gasoline</a></li>
                        <li class="part"><a href="#Gear">Gear</a></li>
                        <li class="part"><a href="#GeigerCounter">GeigerCounter</a></li>
                        <li class="part"><a href="#Generator">Generator</a></li>
                        <li class="part"><a href="#Glass">Glass</a></li>
                        <li class="part"><a href="#Gold">Gold</a></li>
                        <li class="part"><a href="#Goo">Goo</a></li>
                        <li class="part"><a href="#Grass">Grass</a></li>
                        <li class="part"><a href="#GravityGenerator">GravityGenerator</a></li>
                        <li class="part"><a href="#Gun">Gun</a></li>
                        <li class="part"><a href="#Gyro">Gyro</a></li>
                        <li class="part"><a href="#Handle">Handle</a></li>
                        <li class="part"><a href="#Handle">Handle</a></li>
                        <li class="part"><a href="#Hatch">Hatch</a></li>
                        <li class="part"><a href="#Heater">Heater</a></li>
                        <li class="part"><a href="#Heatshield">Heatshield</a></li>
                        <li class="part"><a href="#Helium">Helium</a></li>
                        <li class="part"><a href="#Hologram">Hologram</a></li>
                        <li class="part"><a href="#Hotdog">Hotdog</a></li>
                        <li class="part"><a href="#HttpService">HttpService</a></li>
                        <li class="part"><a href="#HullTemplate">HullTemplate</a></li>
                        <li class="part"><a href="#Hydrogen">Hydrogen</a></li>
                        <li class="part"><a href="#Hydroponic">Hydroponic</a></li>
                        <li class="part"><a href="#HyperDrive">HyperDrive</a></li>
                        <li class="part"><a href="#ID">ID</a></li>
                        <li class="part"><a href="#Ice">Ice</a></li>
                        <li class="part"><a href="#Igniter">Igniter</a></li>
                        <li class="part"><a href="#ImpulseCannon">ImpulseCannon</a></li>
                        <li class="part"><a href="#Instrument">Instrument</a></li>
                        <li class="part"><a href="#IonDrive">IonDrive</a></li>
                        <li class="part"><a href="#IonRocket">IonRocket</a></li>
                        <li class="part"><a href="#Iron">Iron</a></li>
                        <li class="part"><a href="#Jade">Jade</a></li>
                        <li class="part"><a href="#Katana">Katana</a></li>
                        <li class="part"><a href="#Keyboard">Keyboard</a></li>
                        <li class="part"><a href="#Kiln">Kiln</a></li>
                        <li class="part"><a href="#Lantern">Lantern</a></li>
                        <li class="part"><a href="#Laser">Laser</a></li>
                        <li class="part"><a href="#Lava">Lava</a></li>
                    </ul>
                </td>
                <td>
                    <ul>
                        <li class="part"><a href="#Lead">Lead</a></li>
                        <li class="part"><a href="#LifeSensor">LifeSensor</a></li>
                        <li class="part"><a href="#Light">Light</a></li>
                        <li class="part"><a href="#LightBridge">LightBridge</a></li>
                        <li class="part"><a href="#LightTube">LightTube</a></li>
                        <li class="part"><a href="#LiquidTank">LiquidTank</a></li>
                        <li class="part"><a href="#Magnesium">Magnesium</a></li>
                        <li class="part"><a href="#Marble">Marble</a></li>
                        <li class="part"><a href="#Melter">Melter</a></li>
                        <li class="part"><a href="#MessagingService">MessagingService</a></li>
                        <li class="part"><a href="#Microcontroller">Microcontroller</a></li>
                        <li class="part"><a href="#Microphone">Microphone</a></li>
                        <li class="part"><a href="#MiningLaser">MiningLaser</a></li>
                        <li class="part"><a href="#Missile">Missile</a></li>
                        <li class="part"><a href="#Modem">Modem</a></li>
                        <li class="part"><a href="#ModemMessages">ModemMessages</a></li>
                        <li class="part"><a href="#Motor">Motor</a></li>
                        <li class="part"><a href="#MustardGas">MustardGas</a></li>
                        <li class="part"><a href="#Neon">Neon</a></li>
                        <li class="part"><a href="#Neutronium">Neutronium</a></li>
                        <li class="part"><a href="#NightVisionGoggles">NightVisionGoggles</a></li>
                        <li class="part"><a href="#NitrogenOxide">NitrogenOxide</a></li>
                        <li class="part"><a href="#NuclearWaste">NuclearWaste</a></li>
                        <li class="part"><a href="#Obamium">Obamium</a></li>
                        <li class="part"><a href="#Obelisk">Obelisk</a></li>
                        <li class="part"><a href="#ObjectsFolder">ObjectsFolder</a></li>
                        <li class="part"><a href="#Oil">Oil</a></li>
                        <li class="part"><a href="#Perfectium">Perfectium</a></li>
                        <li class="part"><a href="#Petroleum">Petroleum</a></li>
                        <li class="part"><a href="#Pipe">Pipe</a></li>
                        <li class="part"><a href="#Pistol">Pistol</a></li>
                        <li class="part"><a href="#Plasma">Plasma</a></li>
                        <li class="part"><a href="#PlasmaCannon">PlasmaCannon</a></li>
                        <li class="part"><a href="#Plastic">Plastic</a></li>
                        <li class="part"><a href="#Plutonium">Plutonium</a></li>
                        <li class="part"><a href="#PlutoniumCore">PlutoniumCore</a></li>
                        <li class="part"><a href="#Polysilicon">Polysilicon</a></li>
                        <li class="part"><a href="#Port">Port</a></li>
                        <li class="part"><a href="#PowerCell">PowerCell</a></li>
                        <li class="part"><a href="#Primer">Primer</a></li>
                        <li class="part"><a href="#Propeller">Propeller</a></li>
                        <li class="part"><a href="#Prosthetic">Prosthetic</a></li>
                        <li class="part"><a href="#Pulley">Pulley</a></li>
                        <li class="part"><a href="#Pulverizer">Pulverizer</a></li>
                        <li class="part"><a href="#Pump">Pump</a></li>
                        <li class="part"><a href="#Quartz">Quartz</a></li>
                        <li class="part"><a href="#RBXScriptSignal">RBXScriptSignal</a></li>
                        <li class="part"><a href="#RTG">RTG</a></li>
                        <li class="part"><a href="#Radar">Radar</a></li>
                        <li class="part"><a href="#Rail">Rail</a></li>
                        <li class="part"><a href="#Railgun">Railgun</a></li>
                        <li class="part"><a href="#Reactor">Reactor</a></li>
                        <li class="part"><a href="#Refinery">Refinery</a></li>
                        <li class="part"><a href="#RegionCloaker">RegionCloaker</a></li>
                        <li class="part"><a href="#ReinforcedGlass">ReinforcedGlass</a></li>
                        <li class="part"><a href="#Relay">Relay</a></li>
                        <li class="part"><a href="#RemoteControl">RemoteControl</a></li>
                        <li class="part"><a href="#RepairKit">RepairKit</a></li>
                        <li class="part"><a href="#RepairLaser">RepairLaser</a></li>
                        <li class="part"><a href="#ReplicatedStorage">ReplicatedStorage</a></li>
                        <li class="part"><a href="#Rifle">Rifle</a></li>
                        <li class="part"><a href="#Rocket">Rocket</a></li>
                        <li class="part"><a href="#Rotor">Rotor</a></li>
                        <li class="part"><a href="#RoundTemplate">RoundTemplate</a></li>
                        <li class="part"><a href="#RoundTemplate2">RoundTemplate2</a></li>
                        <li class="part"><a href="#Rubber">Rubber</a></li>
                        <li class="part"><a href="#Ruby">Ruby</a></li>
                        <li class="part"><a href="#RustedMetal">RustedMetal</a></li>
                        <li class="part"><a href="#SMG">SMG</a></li>
                        <li class="part"><a href="#Sail">Sail</a></li>
                    </ul>
                </td>
                <td>
                    <ul>
                        <li class="part"><a href="#SalvageLaser">SalvageLaser</a></li>
                        <li class="part"><a href="#Sand">Sand</a></li>
                        <li class="part"><a href="#Scrapper">Scrapper</a></li>
                        <li class="part"><a href="#Screen">Screen</a></li>
                        <li class="part"><a href="#ScubaMask">ScubaMask</a></li>
                        <li class="part"><a href="#Seat">Seat</a></li>
                        <li class="part"><a href="#Shotgun">Shotgun</a></li>
                        <li class="part"><a href="#Sign">Sign</a></li>
                        <li class="part"><a href="#Silicon">Silicon</a></li>
                        <li class="part"><a href="#Snow">Snow</a></li>
                        <li class="part"><a href="#SolarPanel">SolarPanel</a></li>
                        <li class="part"><a href="#SolarScoop">SolarScoop</a></li>
                        <li class="part"><a href="#Sorter">Sorter</a></li>
                        <li class="part"><a href="#SoundMuffler">SoundMuffler</a></li>
                        <li class="part"><a href="#SpawnPoint">SpawnPoint</a></li>
                        <li class="part"><a href="#Speaker">Speaker</a></li>
                        <li class="part"><a href="#Splitter">Splitter</a></li>
                        <li class="part"><a href="#Spotlight">Spotlight</a></li>
                        <li class="part"><a href="#StarMap">StarMap</a></li>
                        <li class="part"><a href="#StasisField">StasisField</a></li>
                        <li class="part"><a href="#Steam">Steam</a></li>
                        <li class="part"><a href="#SteamEngine">SteamEngine</a></li>
                        <li class="part"><a href="#SteamTurbine">SteamTurbine</a></li>
                        <li class="part"><a href="#Stick">Stick</a></li>
                        <li class="part"><a href="#Stone">Stone</a></li>
                        <li class="part"><a href="#StudAligner">StudAligner</a></li>
                        <li class="part"><a href="#Sulfur">Sulfur</a></li>
                        <li class="part"><a href="#Switch">Switch</a></li>
                        <li class="part"><a href="#Teleporter">Teleporter</a></li>
                        <li class="part"><a href="#Telescope">Telescope</a></li>
                        <li class="part"><a href="#TemperatureSensor">TemperatureSensor</a></li>
                        <li class="part"><a href="#TestStarMap">TestStarMap</a></li>
                        <li class="part"><a href="#TetrahedronTemplate">TetrahedronTemplate</a></li>
                        <li class="part"><a href="#Thruster">Thruster</a></li>
                        <li class="part"><a href="#Tile">Tile</a></li>
                        <li class="part"><a href="#TimeSensor">TimeSensor</a></li>
                        <li class="part"><a href="#TintedGlass">TintedGlass</a></li>
                        <li class="part"><a href="#Tire">Tire</a></li>
                        <li class="part"><a href="#Titanium">Titanium</a></li>
                        <li class="part"><a href="#Tool">Tool</a></li>
                        <li class="part"><a href="#Tool">Tool</a></li>
                        <li class="part"><a href="#Torch">Torch</a></li>
                        <li class="part"><a href="#TouchScreen">TouchScreen</a></li>
                        <li class="part"><a href="#TouchSensor">TouchSensor</a></li>
                        <li class="part"><a href="#Transformer">Transformer</a></li>
                        <li class="part"><a href="#Transporter">Transporter</a></li>
                        <li class="part"><a href="#Treads">Treads</a></li>
                        <li class="part"><a href="#TriggerSwitch">TriggerSwitch</a></li>
                        <li class="part"><a href="#TriggerWire">TriggerWire</a></li>
                        <li class="part"><a href="#TrussTemplate">TrussTemplate</a></li>
                        <li class="part"><a href="#Turbofan">Turbofan</a></li>
                        <li class="part"><a href="#Uranium">Uranium</a></li>
                        <li class="part"><a href="#Valve">Valve</a></li>
                        <li class="part"><a href="#VehicleSeat">VehicleSeat</a></li>
                        <li class="part"><a href="#VintagePlasmaPistol">VintagePlasmaPistol</a></li>
                        <li class="part"><a href="#Volume">Volume</a></li>
                        <li class="part"><a href="#Warhead">Warhead</a></li>
                        <li class="part"><a href="#Water">Water</a></li>
                        <li class="part"><a href="#WaterCooler">WaterCooler</a></li>
                        <li class="part"><a href="#WedgeTemplate">WedgeTemplate</a></li>
                        <li class="part"><a href="#Weld">Weld</a></li>
                        <li class="part"><a href="#Weld">Weld</a></li>
                        <li class="part"><a href="#WindTurbine">WindTurbine</a></li>
                        <li class="part"><a href="#Wing">Wing</a></li>
                        <li class="part"><a href="#Wire">Wire</a></li>
                        <li class="part"><a href="#WirelessButton">WirelessButton</a></li>
                        <li class="part"><a href="#Wood">Wood</a></li>
                        <li class="part"><a href="#ZapWire">ZapWire</a></li>
                        <li class="part"><a href="#tinnitus">tinnitus</a></li>
                    </ul>
                </td>
            </tr>
        </tbody>
    </table>
    <!-- ActualParts -->
    <div id="PartItem">
        <h2 id="Wood">Wood</h2>
        <p style="font-family:Verdana">**A natural resource found in trees and flora.** It is a simple and yet effective
            material that is used for simple objects and structures. These can be mainly found in terra and forest
            planets, but can occasionally be found in temperate tundra and desert planets.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 512</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="DelayWire">DelayWire</h2>
        <p style="font-family:Verdana">Similar to a regular trigger wire, but depending on the configuration will wait x
            seconds before the trigger signal passes through. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>DelayTime = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Rubber</li>
                        <li>1 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Hatch">Hatch</h2>
        <p style="font-family:Verdana">Acts as a chute when active/gray, but when black or inactive it acts as a normal
            object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 12*12</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Solid"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>SwitchValue = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Chute</li>
                        <li>1 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Boiler">Boiler</h2>
        <p style="font-family:Verdana">Turns water to steam when fueled with 2 water and 1 coal. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 80
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wire</li>
                        <li>5 Heater</li>
                        <li>25 Pipe</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Extractor">Extractor</h2>
        <p style="font-family:Verdana">Extracts and harvests materials from connected terrain such as mountains and ore
            deposits. For example, to extract coal you attach it to the coal deposit, and configure the extractor to
            extract Coal. The extractor must be powered in order to work. Will not work if there's another powered
            extractor 50 studs away. If connected to a bin, it will supply that bin with the given material it is tasked
            to extract. Two powered extractors cannot be on the same ore deposit, or else they both will not function.
            Two powered extractors also can't be near eachother. If the materials can't be added to a bin, they will
            spawn in front of the hole on the front of the extractor. However, if the extractor is blocked by an object,
            it will not spew out any materials. When tasked to extract wood, it will extract any trees near it.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 30
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>MaterialToExtract = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DevGenerator">DevGenerator</h2>
        <p style="font-family:Verdana">A debug item meant for developers.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1000000</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">DevGenerator
                            generates around 10e10 Power</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="BurstLaser">BurstLaser</h2>
        <p style="font-family:Verdana"> Fires 5 rapid sets of concentrated laser beams. Each beam does a mediate amount
            of damage. Costs 100 power for each beam fired, meaning the total power cost is 500 power. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Jade</li>
                        <li>50 Explosive</li>
                        <li>90 Silicon</li>
                        <li>100 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="IonDrive">IonDrive</h2>
        <p style="font-family:Verdana"> --A more powerful and heavier version of the IonRocket. --Generates a lot of
            heat when powered on, be sure to cool it down or it will combust. -- --Attaching more iondrives will result
            in a higher propulsion speed. -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 60
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Temperature
                            Limit from -30 up to 200</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 30
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Propulsion = 50;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>30 Aluminum</li>
                        <li>2 IonRocket</li>
                        <li>30 Iron</li>
                        <li>5 Gear</li>
                        <li>30 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CrossBow">CrossBow</h2>
        <p style="font-family:Verdana">A cheap primitive ranged weapon.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Cloth</li>
                        <li>2 Stick</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CloningBay">CloningBay</h2>
        <p style="font-family:Verdana">Similar to a SpawnPoint, but allows players to respawn at the location from far
            away even at another region. It is pretty much a cross region spawnpoint. However, you can only have one
            cloning bay at a time. When powered, it will appear in your death menu when you die and you can click it to
            spawn at this location. However, you should pair the CloningBay with a spawn point next to it to ensure you
            spawn at the cloning bay.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 PowerCell</li>
                        <li>1 SpawnPoint</li>
                        <li>25 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Food">Food</h2>
        <p style="font-family:Verdana">A consumable item. *Appears* to be meat. Upon clicking it, it will heal the
            user's health depending on the size.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Grass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Lead">Lead</h2>
        <p style="font-family:Verdana">An uncommon material used in protection against radiation and weapon
            manufacturing.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25*25</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="BlastingCap">BlastingCap</h2>
        <p style="font-family:Verdana">A component used in crafting recipes for more advanced explosive devices.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Gear</li>
                        <li>25 Iron</li>
                        <li>25 Silicon</li>
                        <li>25 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Filter">Filter</h2>
        <p style="font-family:Verdana">Similar to a chute and a pipe, but only lets certain materials pass through.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*8*2</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Filter = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Chute</li>
                        <li>1 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Antenna">Antenna</h2>
        <p style="font-family:Verdana">A wireless transmitter that can transmit electricity from wires and trigger
            signals from trigger wires and buttons. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 5*5</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>AntennaID = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>15 Quartz</li>
                        <li>10 Silicon</li>
                        <li>5 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TetrahedronTemplate">TetrahedronTemplate</h2>
        <p style="font-family:Verdana">A tetrahedron template made of 3 perpendicular right triangles.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Instrument">Instrument</h2>
        <p style="font-family:Verdana"> A device used to measure special values such as current speed and temperature.
            These are the types as follows: 0 - Speed / velocity of the instrument 1 - Rotational speed of the
            instrument 2 - Temperature of the local environment 3 - Current time (relative to the region and scaled to
            earth time) 4 - Total amount of power in a wire system, for example attaching it to a powercell with 200
            power will display 200 power. 5 - The dimensions of the part it is attached to. 6 - The position of the
            current instrument. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*8*1</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>GetReading(OptionalType)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Type = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BladeTemplate">BladeTemplate</h2>
        <p style="font-family:Verdana">A sharp object that can pierce through objects if the material is durable and
            strong. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Teleporter">Teleporter</h2>
        <p style="font-family:Verdana"> A device used to transport players across regions. When powered and triggered,
            it will teleport all players above it to the given coordinates and teleporter id. It will warp the player to
            a teleporter in the region with the given teleporter id. When warping to a teleporter inside of a planet,
            set the last value to true. For example, 50, -50, 85, -75, true Make sure you set the correct coordinates OR
            YOU WILL BE STRANDED! Costs 1000 energy per teleport. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>TeleporterID = 1;</li>
                            <li>Coordinates = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>30 Wire</li>
                        <li>1 HyperDrive</li>
                        <li>50 Quartz</li>
                        <li>1 Transporter</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Water">Water</h2>
        <p style="font-family:Verdana">The basis of all life, and is a liquid found in terra, forest, ocean and certain
            tundras and rogue planets. Can be made from burning ice or snow.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Stick">Stick</h2>
        <p style="font-family:Verdana">A natural resource found in trees and flora, often accompanied by wood. It is
            used for creating vital tools.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Laser">Laser</h2>
        <p style="font-family:Verdana">Fires a concentraded beam of energy when powered, which can be used to damage and
            set objects on fire. Has a Range of 1000 studs. Primarily used as a weapon in space combat situations. While
            it can damage objects effectively, it cannot damage energy shields. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*2*2</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>DamageOnlyPlayers = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Ruby</li>
                        <li>50 Diamond</li>
                        <li>25 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Goo">Goo</h2>
        <p style="font-family:Verdana">A sticky substance that can stick together to objects when touched.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*8</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Grass</li>
                        <li>5 Sand</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="WaterCooler">WaterCooler</h2>
        <p style="font-family:Verdana">Generates cold temperatures when given a supply of water. Useful for cooling down
            devices, and does not require power. Performs the same amount of cooling that five coolers would.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces -100
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 8
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Water</li>
                        <li>10 Pipe</li>
                        <li>4 Copper</li>
                        <li>1 Container</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ExoticMatter">ExoticMatter</h2>
        <p style="font-family:Verdana">???</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="ReinforcedGlass">ReinforcedGlass</h2>
        <p style="font-family:Verdana">A stronger version of glass, however is less malleable.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 14*14</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Iron</li>
                        <li>5 Glass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Explosive">Explosive</h2>
        <p style="font-family:Verdana">Causes an explosion when triggered. You can use a delay wire to make it explode
            after a few seconds and not immediately.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>40 Sulfur</li>
                        <li>10 Cloth</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TestStarMap">TestStarMap</h2>
        <p style="font-family:Verdana"> A developer version of the starmap. Showcases the entire universe. Lag maybe??
            :topkek: </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2048*2048*2048</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 3
                            Power per second</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Fence">Fence</h2>
        <p style="font-family:Verdana">A metal fence. Primarily used to set up walls and gaurd structures and bases.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*100</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Pipe</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ObjectsFolder">ObjectsFolder</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Pulley">Pulley</h2>
        <p style="font-family:Verdana">A special device used to control the length of constraints attached to it. When
            attaching a constraint to the Pulley, click the Pulley first. When the pulley is triggered with polysilicon,
            it will increase or decrease. Default increase value is 1. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>MinPulleyLength = 0;</li>
                            <li>PulleyIncreaseLength = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wood</li>
                        <li>2 Cloth</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DriveBox">DriveBox</h2>
        <p style="font-family:Verdana">When connected to a motor or engine with a rod, it will spin the same speed the
            engine or motor is going. (You must click the drivebox first when creating a rod.) </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 6*6*4</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 5
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Reversal = "false";</li>
                            <li>Ratio = 99;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Quartz</li>
                        <li>5 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="FluidProjector">FluidProjector</h2>
        <p style="font-family:Verdana">A device which projects a field of gas or liquid in front of it which you can
            swim in. Host the universe's greatest pool party! The fluid area can be configureed in size and type. The
            FluidProjector requires power in order to work, and must be supplied with the correct fluid to work. For
            example, the fluid is water, it will need a supplied container of water attached to work.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Fluid = "Water";</li>
                            <li>Size = "10, 10, 10";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Wire</li>
                        <li>500 Pipe</li>
                        <li>100 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ScubaMask">ScubaMask</h2>
        <p style="font-family:Verdana">A set of goggles which can be used to help vision while underwater.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Rubber</li>
                        <li>3 Glass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TimeSensor">TimeSensor</h2>
        <p style="font-family:Verdana"> When the current time matches the same time as the timesensor, it will trigger.
            For example, if the world turns 7:15 it will activate. This is useful for creating dynamic lights that turn
            on only during the night, saving energy. The format should be hour:minute </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*8*1</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Time = "7:30";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Polysilicon</li>
                        <li>1 TriggerWire</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Tool">Tool</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="ElectricFence">ElectricFence</h2>
        <p style="font-family:Verdana"> A special version of the fence which damages upon contact. Requires power to
            electrocute. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*100</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 ZapWire</li>
                        <li>5 Fence</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="EnergyBomb">EnergyBomb</h2>
        <p style="font-family:Verdana">Causes a powerful explosion when triggered. Often used in space combat as a means
            of a powerful missile or torpedo.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>100 Quartz</li>
                        <li>2 BlastingCap</li>
                        <li>5 Explosive</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Pump">Pump</h2>
        <p style="font-family:Verdana">Pumps liquid from the environment into attached containers. For example, a pump
            located in the ocean will pump water when powered.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 2
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>LiquidToPump = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Quartz</li>
                        <li>1 Container</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Aquarium">Aquarium</h2>
        <p style="font-family:Verdana"> --Creates food from the power of fish. Release food with a dispenser. -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>CanBeCraftedFrom = "true";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>100 Water</li>
                        <li>1 Pump</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Torch">Torch</h2>
        <p style="font-family:Verdana">A torch which can be used to provide light.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wood</li>
                        <li>1 Coal</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Assembler">Assembler</h2>
        <p style="font-family:Verdana">Assembles items as configured when the structure is supplied with the required
            power and resources.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 12
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Assemble = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>3 Gear</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Neon">Neon</h2>
        <p style="font-family:Verdana">A building decoration material that glows by itself without requiring power. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 7*7*7</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 ZapWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Chip">Chip</h2>
        <p style="font-family:Verdana">Applies data to a trigger, feeding it to attached trigger objects. -- Works on:
            -- - Controllers: Sets their value -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*5</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Output = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Silicon</li>
                        <li>1 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Cement">Cement</h2>
        <p style="font-family:Verdana">A modern material useful for pavement.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200*1*40</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Stone</li>
                        <li>2 Sand</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="StasisField">StasisField</h2>
        <p style="font-family:Verdana">Creates a 500 stud radius field that prevents any parts or objects around it from
            being dragged. This can be used alongside with a RegionCloaker to create public infrastructure to avoid
            trolling and such. However, in order to function, the shield must be anchored/grounded, and nothing must be
            blocking above it. The shield is also extremely fragile.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 50
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>500 Ruby</li>
                        <li>250 Iron</li>
                        <li>100 PowerCell</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="EnergyGun">EnergyGun</h2>
        <p style="font-family:Verdana">Fires a powerful shot of energy when provided power and triggered.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 14*2*2</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 0
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Temperature
                            Limit from -140 up to 140</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Aluminum</li>
                        <li>10 Ruby</li>
                        <li>20 Glass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="LightBridge">LightBridge</h2>
        <p style="font-family:Verdana">Fires a beam of solid light that can be walked on. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10 * 2 * 10</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 50
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>30 Aluminum</li>
                        <li>15 Ruby</li>
                        <li>15 Jade</li>
                        <li>15 Diamond</li>
                        <li>15 Quartz</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Perfectium">Perfectium</h2>
        <p style="font-family:Verdana">The perfect material. Unbreakable, very stretchable, but is impossibly rare. The
            very sight of it makes you wonder the imperfections of human beings.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2048*2048*2048</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Splitter">Splitter</h2>
        <p style="font-family:Verdana"> --A device that splits certain objects through one of its three surfaces, and
            will rotate between the three surfaces. --For example, gold entering the splitter will go through hole 1 or
            to the left. The next gold to enter will go through hole 2 or to the middle, and then the next goes through
            hole 3 or to the right. -- --The ObjectsToSplit configuration can be formatted like "Gold" or "Gold,
            Aluminium, Wire, PowerCell". --Make sure to include the space infront of the comma. -- --The objects
            entering the splitter must be ungrounded and unanchored. --Requires power to function, and must be grounded
            or anchored. -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ObjectsToSplit = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Quartz</li>
                        <li>2 Copper</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="WirelessButton">WirelessButton</h2>
        <p style="font-family:Verdana">Similar to a button, but can be clicked from infinite distances and cannot be
            used for keybinds. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*5</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Button</li>
                        <li>12 Quartz</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DarkConverter">DarkConverter</h2>
        <p style="font-family:Verdana">Converts attached dark matter bins into energy. 1 unit of dark matter is equal to
            1000 watts of power. However, this generates a ton of heat in the process, nearly up to 200 degrees when
            activated. This means you will need about 10 coolers to avoid combustion. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">DarkConverter
                            generates around 1000 Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Diamond</li>
                        <li>50 Titanium</li>
                        <li>100 Gold</li>
                        <li>10 AlienCore</li>
                        <li>5 Reactor</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Disk">Disk</h2>
        <p style="font-family:Verdana">A programmable object capable of storing data. Has a limit of 10kb of data. Has 4
            functions that allow you to edit the disk. Write(key, value) writes a value to the disk with a key.
            Read(key) returns a given value of a disk. ClearDisk() clears the entire disk. ReadEntireDisk() returns the
            entire disk table. **Be aware, while disks can store userdata values, it cannot save them properly.** </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*20</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>Read(Key)</li>
                            <li>Write(Key, Data)</li>
                            <li>ClearDisk()</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Quartz</li>
                        <li>3 Copper</li>
                        <li>4 Silicon</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="LightTube">LightTube</h2>
        <p style="font-family:Verdana">Emits light when powered with electricity. Can be colored in different ways,
            changing the light color</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*4*4</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>2 Glass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="LifeSensor">LifeSensor</h2>
        <p style="font-family:Verdana">Senses and detects organic life up to a distnace of 2000 studs. Used mainly in
            programming, as is used in alien technology to hunt down organisms such as players. Has a special
            programmable event called 'GetReading()' which returns a table of all organisms, with their positions and
            names. Example: { Player1 = Vector3.new(5, 5, 5); } </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>GetReading()</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wire</li>
                        <li>15 Grass</li>
                        <li>25 Quartz</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Missile">Missile</h2>
        <p style="font-family:Verdana"> Creates propulsion when triggered. It also temporarily generates power when
            triggered, powering objects attached to it such as a light or transformer. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Propulsion = 50;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 TriggerWire</li>
                        <li>20 Sulfur</li>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CornerRoundTemplate">CornerRoundTemplate</h2>
        <p style="font-family:Verdana">A rounded corner shaped template object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ModemMessages">ModemMessages</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Brick">Brick</h2>
        <p style="font-family:Verdana">A cheap material made from baked clay useful for building houses. Its durability
            doubles when anchored on a planet.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*5*20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Water</li>
                        <li>1 Stone</li>
                        <li>1 Sand</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Warhead">Warhead</h2>
        <p style="font-family:Verdana">Causes a powerful explosion when triggered. You can use a delay wire to make it
            explode after a few seconds and not immediately. The only down-side of the warhead is that it is blocked
            completely by energy shields.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>75 Reactor</li>
                        <li>100 Iron</li>
                        <li>3 EnergyBomb</li>
                        <li>15 Explosive</li>
                        <li>6 BlastingCap</li>
                        <li>800 Uranium</li>
                        <li>70 Primer</li>
                        <li>1 PlutoniumCore</li>
                        <li>1 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Transformer">Transformer</h2>
        <p style="font-family:Verdana">Sends continuous trigger signals every second when powered.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*4*4</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>LoopTime = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Quartz</li>
                        <li>5 Copper</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Fireworks">Fireworks</h2>
        <p style="font-family:Verdana">Causes an explosion when triggered. You can use a delay wire to make it explode
            after a few seconds and not immediately.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>20 Sulfur</li>
                        <li>10 Cloth</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Cleat">Cleat</h2>
        <p style="font-family:Verdana">A textile resource similar to Rubber, except it has a high amount of friction and
            low bounciness. It can be used in physical machines such as the feet of mechs, etc.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*15</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Rubber</li>
                        <li>2 Cloth</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Pistol">Pistol</h2>
        <p style="font-family:Verdana">A simple repeating firearm. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>20 Rubber</li>
                        <li>70 Iron</li>
                        <li>3 Explosive</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="LiquidTank">LiquidTank</h2>
        <p style="font-family:Verdana">A special type of container that only stores liquid, but is able to store more.
            Can store up to 50k liquids.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Rubber</li>
                        <li>2 Container</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Melter">Melter</h2>
        <p style="font-family:Verdana">Turns attached ice bins into water when powered. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wire</li>
                        <li>2 Heater</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="PowerCell">PowerCell</h2>
        <p style="font-family:Verdana"> Stores electricity, and is used to power many devices using wires or by directly
            attaching it. Has a limit of 125000. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10*10</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Wire</li>
                        <li>1 Sulfur</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="PlasmaCannon">PlasmaCannon</h2>
        <p style="font-family:Verdana"> Fires an orb of unstable plasma out of the barrel exploding on impact. Needs to
            be fueled with 500 power and 50 helium or 1 plasma to fire. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>30 Aluminum</li>
                        <li>5 Uranium</li>
                        <li>200 Iron</li>
                        <li>90 Silicon</li>
                        <li>50 Explosive</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Treads">Treads</h2>
        <p style="font-family:Verdana">When touching in contact with a solid surface, it will move forward. Must be
            connected to an engine or motor similar to a drivebox to function. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*2*20</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>16 Gear</li>
                        <li>2 Engine</li>
                        <li>2 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Marble">Marble</h2>
        <p style="font-family:Verdana">A compact and durable material. Primarily used as a building material for
            decorations.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*15*15</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Stone</li>
                        <li>1 Quartz</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CrudeWing">CrudeWing</h2>
        <p style="font-family:Verdana">Creates lift from being pushed forward. A worse version of a Wing. Does not work
            in space or in non atmospheric planets. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*1*8</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Cloth</li>
                        <li>3 Stick</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Quartz">Quartz</h2>
        <p style="font-family:Verdana">A translucent and malleable crystal useful for making durable windows. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 5*5*5</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="SteamEngine">SteamEngine</h2>
        <p style="font-family:Verdana">It acts similar to a motor, but is powered by Steam instead of electricity. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 5
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 0.1
                            Steam per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>EngineSpeed = 10;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Iron</li>
                        <li>4 Pipe</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Microcontroller">Microcontroller</h2>
        <p style="font-family:Verdana">Runs computer programs when triggered and powered. When triggered by an activator
            polysilicon, it will run code. When triggered by a deactivator polysilicon, it will stop running code. For
            more information on pilot.lua or the game's programming system, visit the programming tutorial or visit the
            wiki for the game online. Requires 5 power per second when running. Microcontroller Globals: void
            **Beep**(number Pitch) - default pitch 1, max 10 beeps playing concurrently object **GetPort**(number
            PortID) - returns port configured with 'PortID' object **GetPartFromPort**(object/number Port, string
            ClassName) - gets a part connected to port 'Port' with classname 'ClassName' void
            **TriggerPort**(object/number Port) - sends a trigger signal from the port 'Port' Globals also include all
            lua globals and all rbx.lua globals, except for roblox script-related or game-related globals such as
            workspace, game, stats, time, etc. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>Communicate(Varient)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>StartOnSpawn = "false";</li>
                            <li>Code = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Quartz</li>
                        <li>5 Silicon</li>
                        <li>5 Copper</li>
                        <li>5 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Plutonium">Plutonium</h2>
        <p style="font-family:Verdana">A highly radioactive compound used in manufacturing nuclear explosives.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 NuclearWaste</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Speaker">Speaker</h2>
        <p style="font-family:Verdana">Plays audio of length up to 5 seconds, unless it is powered in which case it can
            play a full audio. When clicked or triggered, it will toggle playing music and will play the song id you
            give it.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 16</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>Chat(Message)</li>
                            <li>ClearSounds()</li>
                            <li>newindex(tab, ind, val)</li>
                            <li>PlaySound(ID)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Audio = 5289642056;</li>
                            <li>Pitch = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Cloth</li>
                        <li>3 Wire</li>
                        <li>2 Motor</li>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Cloth">Cloth</h2>
        <p style="font-family:Verdana">A soft thin fabric that can soak up liquids.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*15</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Grass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="FingerprintSensor">FingerprintSensor</h2>
        <p style="font-family:Verdana"> A special type of button which only activates if the player who clicks is the
            player who locked it or is in the list of players that can be configured. Format for the list should be
            "Player1, Player2, Player3" etc.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*5</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>AllowedPlayers = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Button</li>
                        <li>2 Copper</li>
                        <li>2 Silicon</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Stone">Stone</h2>
        <p style="font-family:Verdana">A resource found in nearly all planets. It is not recommended to use for
            structures, but is often used in crafting simple objects.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*20</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="SoundMuffler">SoundMuffler</h2>
        <p style="font-family:Verdana">A SoundMuffler will silences the sounds of machinery around it.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>20 Cloth</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Lantern">Lantern</h2>
        <p style="font-family:Verdana">A handheld lantern which can be used to provide light.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Light</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="VehicleSeat">VehicleSeat</h2>
        <p style="font-family:Verdana"> Allows players to control vehicles by rotating when sat on. It is incredibly
            important to have when creating vehicles. The vehicleseat has 2 modes. Mode 0 allows it to only rotate
            horizontally. Mode 1 allows it to rotate both horizontally and vertically. Mode 2 points the vehicle seat
            towards the player's mouse when holding click. Attaching buttons to the vehicleseat will allow the player
            sitting on it to trigger the button by pressing a key. Simply attach the button to the vehicle seat,
            configure it to the keybind you would like, and it will allow you to trigger that button by pressing the key
            when sitting down in the seat. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*3</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Speed = 1;</li>
                            <li>Mode = 1;</li>
                            <li>Enabled = "true";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Wood</li>
                        <li>2 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TriggerWire">TriggerWire</h2>
        <p style="font-family:Verdana">Allows trigger objects to interact with each other when connected by
            triggerwires. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Wire</li>
                        <li>1 Flint</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RTG">RTG</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">RTG generates
                            around 15 Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Aluminum</li>
                        <li>15 ExoticMatter</li>
                        <li>2 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Transporter">Transporter</h2>
        <p style="font-family:Verdana"> Acts as an antenna but for bins and objects containing materials such as liquids
            and solids. Useful for creating large factory bases with many extractors without using long chutes. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>TransporterID = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Quartz</li>
                        <li>2 Antenna</li>
                        <li>15 Chute</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Controller">Controller</h2>
        <p style="font-family:Verdana">Acts as a wire when active/green, but when black or inactive it acts as a normal
            object. Must use a polysilicon to switch for trigger events. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 13*13</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Iron</li>
                        <li>4 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Obelisk">Obelisk</h2>
        <p style="font-family:Verdana">An object designed to attract aliens to the region. Emits an ominous noise when
            powered. Must be anchored and powered in order to function. Must also be open to the sky. Only one obelisk
            in a region can be powered at a time. **Use at your own risk.**</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 15
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Wire</li>
                        <li>250 Diamond</li>
                        <li>10 AlienCore</li>
                        <li>500 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Motor">Motor</h2>
        <p style="font-family:Verdana">Spins objects attached to the hinge at the front when powered. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 6*6*4</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 5
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>MotorSpeed = 10;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Engine</li>
                        <li>3 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Aluminum">Aluminum</h2>
        <p style="font-family:Verdana">A light material useful for air transport. Isn't very durable. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 30*30*30</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Telescope">Telescope</h2>
        <p style="font-family:Verdana"> A device that allows you to look at celestial objects and regions of space from
            a far away distance. Simply click the device and an interface will pop up on your screen allowing you to see
            the image. To view a specific coordinate, configure the telescope and set to the desired coordinates. Can
            only see within 100 universe units, any farther will result in a blurry image. Information such as resources
            on the planet, temperature, distance from its local sun, and planet type will be displayed as well. Must be
            powered in order to view object's information. Has a 1 minute delay between viewing different systems. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>GetCoordinate(x1, y1, x2, y2)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ViewCoordinates = "0, 0, 0, 0";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>15 Wire</li>
                        <li>5 Glass</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Spotlight">Spotlight</h2>
        <p style="font-family:Verdana">Emits light in a cone when powered with electricity. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*8*4</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>1 Glass</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Reactor">Reactor</h2>
        <p style="font-family:Verdana">Generates steam using water and heat from radiation. Up to 4 pieces of uranium
            can be inserted into the reactor as fuel. If the temperature is above 400, it will begin to turn water into
            steam (rate dependent on temperature). If the temperature exceeds 1200 F, a meltdown will occur. The Reactor
            fuel status can be acquired through the Reactor:GetFuel() method with a microcontroller. Polysilicon is used
            to control a reactor, and fuel must be ejected manually: Mode 0 will lower the control rods. Mode 1 will
            raise the control rods (allowing fuel to be used). Mode 2 will eject fuel or waste from the fuel rod with
            the least fuel.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Reactor
                            generates around 0 Steam</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul></ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Quartz</li>
                        <li>25 Pipe</li>
                        <li>50 Iron</li>
                        <li>15 Wire</li>
                        <li>30 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Prosthetic">Prosthetic</h2>
        <p style="font-family:Verdana"> An artificial part that can be attached to players in exchange for a limb. The
            limb configuration can be configureed to be the limb you want to have for a prosthetic, for example
            configuring it to be "Right Leg" will have the prosthetic attach itself to your character. Simply touch the
            prosthetic, and it will automatically be attached to your body. Parts can be attached to the prosthetic,
            allowing many uses for the prosthetic limb. Prosthetic limbs are also electrically conductable, acting as a
            wire. Heavily damages the character once attached. Prosthetics can't have more than 50 parts attached to
            them. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Limb = "Left Arm";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Wire</li>
                        <li>25 Rubber</li>
                        <li>25 Quartz</li>
                        <li>25 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Decoupler">Decoupler</h2>
        <p style="font-family:Verdana">When triggered, it breaks welds and falls off of anything attached. Can be used
            to separate things.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*2*8</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>12 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Snow">Snow</h2>
        <p style="font-family:Verdana">An abundant resource that can be found in terra biomes and tundra planets. When
            burnt, the snow turns into water.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25*25</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="RoundTemplate2">RoundTemplate2</h2>
        <p style="font-family:Verdana">A block rounded inwards on one edge. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="HyperDrive">HyperDrive</h2>
        <p style="font-family:Verdana"> A device used to travel at faster than light speeds to other regions of the
            universe. Simply input the coordinates to your destination and have the sufficient amounts of fuel, and
            you'll be on your way to your destination. To initiate warping, power the hyperdrive and trigger it. When
            warping, the hyperdrive will be anchored to prevent any movement. The power required for warping will be
            dependent on the distance travelled, as well as the size of the object being transported. The amount of
            power required will be displayed in the hyper drive, shown in the red text. All of the parts connected to
            the hyperdrive and every player sitting will be teleported, however any free floating parts or standing up
            players will be sucked into the vaccum of space, so be careful. The red text at the bottom of the hyperdrive
            indicates how much power is needed to perform the jump. Make sure the numbers on the hyperdrive is facing up
            to ensure correct stud alignment. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul></ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Wire</li>
                        <li>3 IonRocket</li>
                        <li>100 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CameraEvent">CameraEvent</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="TriggerSwitch">TriggerSwitch</h2>
        <p style="font-family:Verdana">Acts as a triggerwire when active/green, but when black or inactive it acts as a
            normal object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 12*12</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>SwitchValue = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Silicon</li>
                        <li>1 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="SolarPanel">SolarPanel</h2>
        <p style="font-family:Verdana">Generates electricity using solar energy from a local star. The closer it is to a
            star, the more energy it generates. The type of star also affects its energy generation, as well as the size
            of the solar panel. If the solar panel is blocked by a part, it will not generate any energy. Glass however
            will work. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1000</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">SolarPanel
                            generates around 0 end local RayCheck = Ray.new(Object.Position, Vector3.new(0, 200, 0))
                            local FindHit = workspace:FindPartOnRayWithIgnoreList(RayCheck,
                            Services.CollectionService:GetTagged("Translucent")) if FindHit then self.GeneratorAmount =
                            0 end end Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Wire</li>
                        <li>40 Quartz</li>
                        <li>7 Silicon</li>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Boombox">Boombox</h2>
        <p style="font-family:Verdana">Must be powered in order to play music. When clicked, it will toggle playing
            music and will play the song id you give it.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Audio = 4715885427;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Quartz</li>
                        <li>2 Glass</li>
                        <li>2 Copper</li>
                        <li>4 Iron</li>
                        <li>4 Motor</li>
                        <li>3 Pipe</li>
                        <li>4 Cloth</li>
                        <li>6 Gear</li>
                        <li>5 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RepairKit">RepairKit</h2>
        <p style="font-family:Verdana">A useful kit of tools that can be used to repair objects which have been damaged.
            Keep away from biters. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Igniter">Igniter</h2>
        <p style="font-family:Verdana">Sets alight parts within the immediate vicinity when triggered.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*2*2</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>5 Plastic</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="FactionSpawn">FactionSpawn</h2>
        <p style="font-family:Verdana">Acts as a spawn location for the faction of the player who locked it.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Diamond</li>
                        <li>10 SpawnPoint</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DeleteSwitch">DeleteSwitch</h2>
        <p style="font-family:Verdana">An object that deletes itself when triggered.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 12*12</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Silicon</li>
                        <li>1 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Electromagnet">Electromagnet</h2>
        <p style="font-family:Verdana">A powerful magnet.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1*5*5</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 14
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>100 Wire</li>
                        <li>20 Copper</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="SpawnPoint">SpawnPoint</h2>
        <p style="font-family:Verdana">Acts as a spawn location for the player who locked it.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Rubber">Rubber</h2>
        <p style="font-family:Verdana">A textile resource used in manufacturing many industrial objects.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*15</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                        <li>1 Grass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RoundTemplate">RoundTemplate</h2>
        <p style="font-family:Verdana">A block rounded on one edge, or 1/4 of a cylinder. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Scrapper">Scrapper</h2>
        <p style="font-family:Verdana">Scraps solid items provided through a dispenser into their crafting components
            when powered. It also destroys unanchored single parts when touched.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 12
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Ruby">Ruby</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*4*2</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Gun">Gun</h2>
        <p style="font-family:Verdana"> Fires a harmful bullet when triggered. Must be supplied with ammo in order to
            function. For example, you need an iron bin with 1 or more iron directly attached to it to work. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10*15</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>12 Sulfur</li>
                        <li>6 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Flamethrower">Flamethrower</h2>
        <p style="font-family:Verdana">Shoots a stream of flaming gasoline to ignite your foes.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*25*3</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Rubber</li>
                        <li>8 Flint</li>
                        <li>8 Sulfur</li>
                        <li>24 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Light">Light</h2>
        <p style="font-family:Verdana">Emits light when powered with electricity. Can be colored in different ways,
            changing the light color</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*4*4</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>LightRange = 60;</li>
                            <li>Brightness = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>2 Glass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Balloon">Balloon</h2>
        <p style="font-family:Verdana">Levitates parts attached to it to a certain configurable height. However, it is
            easily poppable. Does not work in space, or no-atmosphere planets.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 50*50*10</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Buoyancy = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Rubber</li>
                        <li>3 Cloth</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BeamRifle">BeamRifle</h2>
        <p style="font-family:Verdana">A deadly long-range energy sniper. Able to pick off targets at a long range with
            exceptional accuracy. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Aluminum</li>
                        <li>10 Diamond</li>
                        <li>30 Titanium</li>
                        <li>5 EnergyBomb</li>
                        <li>2 Ruby</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Kiln">Kiln</h2>
        <p style="font-family:Verdana">Turns attached sand bins into glass. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wire</li>
                        <li>2 Heater</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Glass">Glass</h2>
        <p style="font-family:Verdana"> Created when sand is burned or set on fire. Can be broken by heavy impacts or by
            fist.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="SolarScoop">SolarScoop</h2>
        <p style="font-family:Verdana"> Extracts materials from a star when powered and pointed at a star. Depending on
            the class of the star, it will extract more materials. Generates around 240 degrees of heat, meaning you
            will need atleast 12 coolers to cool it down. Red stars generate 25 helium, 5 plasma and 10 hydrogen per
            second. Orange stars generate 30 helium, 5 plasma and and 15 hydrogen per second. Yellow stars generate 35
            helium, 5 plasma and and 20 hydrogen per second. Light blue stars generate 40 helium, 25 hydrogen, 10 plasma
            and and 10 iron per second. Neutron stars generate 60 helium, 45 hydrogen, 15 plasma and and 20 iron per
            second. It also generates 1-2 neutronium every 2 minutes. It is recommended to use a Filter to seperate the
            materials extracted by a solar scoop. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 100
                            heat when powered</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 50
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Reactor</li>
                        <li>500 Ruby</li>
                        <li>25 MiningLaser</li>
                        <li>15 AlienCore</li>
                        <li>100 Bin</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Rail">Rail</h2>
        <p style="font-family:Verdana">Slides and moves objects along its surface when powered and triggered. Useful for
            creating retractable pistons and actuators, for turrets or other retractable devices. Rails will only move
            objects connected on the relative top surface of the rail. The rail can only be activated through the use of
            polysilicons. Mode 0 or activating polysilicons will set the rail to position1. Mode 1 or deactivating
            polysilicons will set the rail to position2. Mode 2 or flip flop polysilicons will act like a switch,
            setting to position2 if position1 and vice versa. Has 2 configurations, position1 and position2. Both
            configurations should be between 0 and 100. These are percents of where the attached objects should slide
            to. For example, if a rail was 50 studs long and position2 was 50 or 50%, the attached objects will slide to
            the middle or at 25 studs. Due to roblox physics, rails may act weirdly. To prevent this from happening, you
            should always place your rails first before anything else. It is recommended to attach objects on the rail
            after the rail is safely placed down. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>SetPosition(PosNumber)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Position1 = 0;</li>
                            <li>TweenTime = 1;</li>
                            <li>Position2 = 100;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Gear</li>
                        <li>4 Rubber</li>
                        <li>3 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RepairLaser">RepairLaser</h2>
        <p style="font-family:Verdana"> --Fires a concentraded beam of energy when powered, which is used to repair
            damaged objects. Useful for repairing damaged vehicles, bases, ships, etc. -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 50
                            heat when powered</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*4*4</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 30
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul></ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>20 Aluminum</li>
                        <li>10 Jade</li>
                        <li>2 Laser</li>
                        <li>20 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Polysilicon">Polysilicon</h2>
        <p style="font-family:Verdana">A special electronic material used to send special signals to certain objects. If
            mode is set to 0, it activates. If set to mode 1, it deactivates. If set to mode 2, it flip flops. Has a
            special configuration called Frequency which dictates how many times the polysilicon will repeat a trigger.
            For example, if a polysilicon was attached to a pulley, having a frequency of 5 and triggered, the pulley
            will be activated 5 times.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Frequency = 1;</li>
                            <li>PolysiliconMode = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Quartz</li>
                        <li>1 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BallastTank">BallastTank</h2>
        <p style="font-family:Verdana">Allows for variable ballast to be added to sea vehicles. Also prevents corrosion
            to attached parts underwater. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Buoyancy = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Aluminum</li>
                        <li>1 Rubber</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Pulverizer">Pulverizer</h2>
        <p style="font-family:Verdana">Turns attached stone bins into sand. Once powered, the pulverizer will pulverize
            any stone bins attached into sand.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 3
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Wire</li>
                        <li>3 Gear</li>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Gear">Gear</h2>
        <p style="font-family:Verdana">A mechanical component commonly used in crafting recipes for many objects.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Cannon">Cannon</h2>
        <p style="font-family:Verdana"> Fires a cannon ball when triggered or clicked. Inserting materials gives it
            different cannon types. For example, inserting iron will result in one powerful iron cannonball being shot.
            Inserting copper will result in multiple copper cannonballs shot. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*2*20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Flint</li>
                        <li>4 Sulfur</li>
                        <li>12 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="HttpService">HttpService</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Pipe">Pipe</h2>
        <p style="font-family:Verdana">Is able to transfer liquids and gases between containers and other objects when
            connected by pipes. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "LiquidGas"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="EthernetCable">EthernetCable</h2>
        <p style="font-family:Verdana">Allows for the transfer of data between ports. Mostly utilized in programming.
        </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*10</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="AutomaticLaser">AutomaticLaser</h2>
        <p style="font-family:Verdana"> Fires a continous set of lasers when powered. Like most other energy/thermal
            weapons, it generates heat when powered. It generates up to 65 degrees of heat, meaning you will need
            atleast 2 or 3 coolers. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 65
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Jade</li>
                        <li>50 Explosive</li>
                        <li>90 Silicon</li>
                        <li>200 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Faucet">Faucet</h2>
        <p style="font-family:Verdana">Releases liquids and gases from containers.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1 * 8 * 1</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 0
                            LiquidGas per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Rubber</li>
                        <li>1 Pipe</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="NightVisionGoggles">NightVisionGoggles</h2>
        <p style="font-family:Verdana">A set of goggles which can be used to see in the dark.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Wire</li>
                        <li>2 Glass</li>
                        <li>1 Ruby</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ReplicatedStorage">ReplicatedStorage</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Thruster">Thruster</h2>
        <p style="font-family:Verdana">A device that creates forward propulsion depending on its size when powered. The
            size of the thruster will determine the max thrust speed it can have, with a larger thruster being capable
            of higher speeds. The speed setting of the thruster can also be configured from -100 (full backward) to 100
            (full forward). The maximum speed of a thruster is dependent on its volume. Thrusters will generate more
            heat the larger and more powerful the thruster is. A 10x10x10 thruster, for example, would need about 8
            coolers to operate. The power required by a thruster is proportional to its actual speed output. Thrusters
            can be heated to a temperature of around 200 degrees before overheating and combusting.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*20*20</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 70
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Temperature
                            Limit from -30 up to 200</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 30
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Propulsion = 50;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Wire</li>
                        <li>20 Pipe</li>
                        <li>1 Motor</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CornerRoundTemplate2">CornerRoundTemplate2</h2>
        <p style="font-family:Verdana">A corner shaped template object rounded inwards. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Volume">Volume</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody></tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="CombustionTurbine">CombustionTurbine</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 200
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">
                            CombustionTurbine generates around 80 Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Pipe</li>
                        <li>20 Iron</li>
                        <li>5 Gear</li>
                        <li>3 Engine</li>
                        <li>10 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TouchScreen">TouchScreen</h2>
        <p style="font-family:Verdana">A Screen, but with capabilities of handling player mouse input. This is to be
            used with programming.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>GetCursors()</li>
                            <li>GetCursor()</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>VideoID = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Copper</li>
                        <li>2 Iron</li>
                        <li>1 TouchTrigger</li>
                        <li>1 Screen</li>
                        <li>3 Silicon</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="GeigerCounter">GeigerCounter</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 12</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wire</li>
                        <li>5 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Camera">Camera</h2>
        <p style="font-family:Verdana">It's a camera. When a camera has the same ID as a screen, that screen will
            display the camera view. Clicking on a screen that is displaying the view of a camera will allow you to
            directly view what the camera is seeing. No power is necessary.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>VideoID = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Quartz</li>
                        <li>2 Wire</li>
                        <li>2 Silicon</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Gasoline">Gasoline</h2>
        <p style="font-family:Verdana">A liquid used for fueling many devices such as rockets and engines.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Iron">Iron</h2>
        <p style="font-family:Verdana">A compact and durable material, commonly found in planets. It is used often in
            crafting, and is a very important resource to have.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25*25</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Claymore">Claymore</h2>
        <p style="font-family:Verdana">A classic medieval sword used to cut down your enemies. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Rubber</li>
                        <li>1 Stick</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Coal">Coal</h2>
        <p style="font-family:Verdana">A natural resource found abundant in mountains, and is commonly used as a source
            of generating heat and energy. Can be placed in a BurnerGenerator to generate energy.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*3*3</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="ChemicalSynthiser">ChemicalSynthiser</h2>
        <p style="font-family:Verdana">Synthesizes and mixes chemical compounds. Consumes matter out of attached bins in
            order to fuel the material synthesis. 1 Nitrogen + 3 Hydrogen = 2 Ammonia 1 Ammonia + 1 Ethanol =
            Diethylamine 2 Hydrogen + 2 Oxygen = Hydrogen Peroxide 2 Hydrogen + 1 Oxygen = Water 1 Sodium + 1 Chlorine =
            Salt 2 Oxygen + 1 Carbon = Carbon Dioxide 2 Nitrogen + 1 Oxygen = Laughing gas/N2O 3 Chlorine + 1 Ethanol +
            1 Water = Chloral Hydrate 1 Potassium + 1 Water = Explosion 1 Potassium Ingested = Explosion 1 Sodium + 1
            Oxygen + 1 Hydrogen = 1 Lye 2 Oil + 1 Lye = Napalm 1 Diethylamine + 1 Ammonia + 1 Lithium + 1 Phosphorus =
            Hallucinogenic Compound 1 Salt + 1 Lithium + 1 Silicon + 1 Hydrogen = Hallucinogenic Toxin 1 Ammonia + 1 Oil
            + 1 Oxygen = Cyanide 1 Chlorine + 1 Ammonia = Mustard gas 1 Lithium + 1 Mercury = Toxin 1 Fluorine + 1
            Hydrogen + 1 Potassium + 1 Sulphuric Acid = Fluorosulfuric Acid 1 Fluorosulfuric Acid + 1 Hydrogen Peroxide
            + 1 Nitrogen = Nitric Acid </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>7 Wire</li>
                        <li>10 Glass</li>
                        <li>1 Microcontroller</li>
                        <li>1 Aluminum</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="FireWood">FireWood</h2>
        <p style="font-family:Verdana">A version of wood that is able to burn longer, allowing it to be an efficient
            fire burning device.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 5*2*2</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wood</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="HullTemplate">HullTemplate</h2>
        <p style="font-family:Verdana">Is able to float in the water, as well as carry objects attached to it. Primarily
            used for creating boats and other water craft. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="MiningLaser">MiningLaser</h2>
        <p style="font-family:Verdana"> Fires a concentraded beam of energy when powered, which is used to mine objects
            such as asteroids, mountains and ore deposits. This works similar to an extractor, except it indirectly
            extracts power from other natural sources. When the laser hits an object, it will extract resources from
            that object and put it in attached bins. Very useful for creating mining vehicles to extract resources.
            Unlike the extractor however, this is far more efficient. The MiningLaser outputs 2 resources per second,
            unlike the extractor which only does 2. This means the laser is 1.5x more efficient. However, the mining
            laser generates more heat than the extractor. Atleast 2 coolers are recommended per mining laser. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 50
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*4*4</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>MaterialToExtract = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Aluminum</li>
                        <li>5 Extractor</li>
                        <li>2 Laser</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Container">Container</h2>
        <p style="font-family:Verdana">Stores liquids and gases. When a liquid or gas touches the Container, the
            container will automatically store it. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10*10</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Rubber</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TintedGlass">TintedGlass</h2>
        <p style="font-family:Verdana">A material similar to Glass, but is tinted black on the front.. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Flint</li>
                        <li>1 Glass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="IonRocket">IonRocket</h2>
        <p style="font-family:Verdana">An IonRocket allows space flight. When powered, it will propel force dependent on
            the Propulsion setting, which you can configure with the hammer tool. The arrow indicates the direction the
            ionrocket will propel to when powered. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 40
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Temperature
                            Limit from -30 up to 160</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Propulsion = 50;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>15 Wire</li>
                        <li>25 Pipe</li>
                        <li>10 Engine</li>
                        <li>5 PowerCell</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Petroleum">Petroleum</h2>
        <p style="font-family:Verdana">A gas used for creating plastic.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Generator">Generator</h2>
        <p style="font-family:Verdana">Creates energy from rotation. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Generator
                            generates around 0 Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Asphalt">Asphalt</h2>
        <p style="font-family:Verdana">A modern material useful for smooth road surfaces. Its durability triples when
            anchored.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200*1*40</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Stone</li>
                        <li>1 Water</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Ice">Ice</h2>
        <p style="font-family:Verdana">A compact natural resource found in tundra planets and the top of a few
            mountains. It is a slippery material, and has very low friction which can be useful in some devices. Burning
            ice results in water.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 5*5*5</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="StarMap">StarMap</h2>
        <p style="font-family:Verdana"> Shows your current location in the universe and other nearby stars and celestial
            bodies. Has 2 modes, universe and solar. Universe mode shows your location in the universe, and solar mode
            shows your location in the solar system if you are in one. Requires power in order to function. It also has
            unique icons for every celestial body type. Clicking on a Icon will set a single connected HyperDrive to
            those coordinates. When triggered with polysilicon, polysilicon 0 will set it to univesre mode, polysilicon
            1 will set it to solar system mode, and polysilicon 2 will switch it. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*20*25</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 3
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>GetSystems()</li>
                            <li>GetBodies()</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Quartz</li>
                        <li>20 Wire</li>
                        <li>2 Radar</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Flashlight">Flashlight</h2>
        <p style="font-family:Verdana">A flashlight which can be used to provide light.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Light</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Coupler">Coupler</h2>
        <p style="font-family:Verdana">The coupler is a part that allows the coupling/connection of vehicles and objects
            when powered. Both couplers must be powered in order to couple together. When the coupler comes in contact
            with another coupler, the couplers will both connect to eachother, both holes facing eachother. To ensure no
            weld complications, make sure the couplers' triangles are facing upwards. When the couplers connect, the
            white triangles will make a square. Couplers also only couple to other couples with the same CouplerID. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*1*4</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>CouplerID = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Plastic">Plastic</h2>
        <p style="font-family:Verdana">A cheap material made from petroleum and Coal through polymerisation inside
            assemblers.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 40*40*40</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Petroleum</li>
                        <li>1 Coal</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Propeller">Propeller</h2>
        <p style="font-family:Verdana">Propellers propel forward when spun. Forward direction indicated by white spot.
            Does not work in space or non atmospheric planets. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Copper</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Obamium">Obamium</h2>
        <p style="font-family:Verdana">An ancient artifact left behind from an alternate reality.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Grass</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Steam">Steam</h2>
        <p style="font-family:Verdana">A result of water being heated up to high temperatures.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="MustardGas">MustardGas</h2>
        <p style="font-family:Verdana">A heavy chemical warfare weapon used to damage organisms. Gas Masks nullify the
            effects of this gas.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Sulfur</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="NitrogenOxide">NitrogenOxide</h2>
        <p style="font-family:Verdana">A light gas emitted from machines such as extractors and rockets. Inhaling can
            cause severe lung damage.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Helium">Helium</h2>
        <p style="font-family:Verdana">A light invisible odorless gas, floats up. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Hologram">Hologram</h2>
        <p style="font-family:Verdana">Using our brand new Multi-Dimensional Holographic Projection Technology™ you are
            able to create a stationary clone with only the ID of the user provided!.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 7
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>UserId = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Quartz</li>
                        <li>5 Diamond</li>
                        <li>15 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CylinderTemplate">CylinderTemplate</h2>
        <p style="font-family:Verdana">A cylinder shaped template object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="PlutoniumCore">PlutoniumCore</h2>
        <p style="font-family:Verdana">A volatile core close to going supercritical used in recipes for Nuclear
            explosives.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>350 Beryllium</li>
                        <li>50 Plutonium</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Seat">Seat</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wood</li>
                        <li>1 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Switch">Switch</h2>
        <p style="font-family:Verdana">Acts as a wire when active/green, but when black or inactive it acts as a normal
            object. Must use a polysilicon to switch for trigger events. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 12*12</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Power"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>SwitchValue = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Wire</li>
                        <li>2 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CornerTetraTemplate">CornerTetraTemplate</h2>
        <p style="font-family:Verdana">A template which is a tetrahedron subtracted from a cube.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BallTemplate">BallTemplate</h2>
        <p style="font-family:Verdana">A ball shaped template object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="CornerTemplate">CornerTemplate</h2>
        <p style="font-family:Verdana">A corner wedge shaped template object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Valve">Valve</h2>
        <p style="font-family:Verdana">Acts as a pipe when active/gray, but when black or inactive it acts as a normal
            object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 12*12</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "LiquidGas"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>SwitchValue = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Rubber</li>
                        <li>1 Pipe</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TrussTemplate">TrussTemplate</h2>
        <p style="font-family:Verdana">Used as a ladder.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="StudAligner">StudAligner</h2>
        <p style="font-family:Verdana"> An integral part for creating vehicles, it aligns them to be viable for saving.
            This is important due to a bug in roblox called 'part shift' in which precision of numbers is lost during
            saving. As a result, parts will move a tiny bit, which results in dramatic changes to a vehicle. This part
            solves that, by alligned the vehicle to a whole number position, allowing it to be saved properly. Make sure
            the arrow is facing up. To stud align your vehicle, make sure it is unanchored and simply trigger the stud
            alligner. Once it aligns the vehicle, it will anchor all anchors attached. Make sure to also allign at a
            viable and proper place to prevent any noclip glitches during alignment. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Screen">Screen</h2>
        <p style="font-family:Verdana">A programmable object capable of showing text, buttons and images on an LED
            display. Very useful for creating custom programmable interfaces. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>ClearElements(Properties)</li>
                            <li>CreateElement(ElementName, Properties)</li>
                            <li>GetDimensions()</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>VideoID = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Quartz</li>
                        <li>3 Copper</li>
                        <li>3 Iron</li>
                        <li>3 Silicon</li>
                        <li>5 Light</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Freezer">Freezer</h2>
        <p style="font-family:Verdana">Turns attached water bins into ice when powered. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Wire</li>
                        <li>2 Cooler</li>
                        <li>10 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Apparel">Apparel</h2>
        <p style="font-family:Verdana"> A piece of clothing that can be worn by other players. Parts can also be
            attached to the apparel, meaning you can create your own suits with the apprel. It is similar to the
            prosthetic, except it can be taken off and does not cause damage. However, electricity does not trasmit
            throughout the apparel unlike prosthetics. Apparel can also holds less parts than the prosthetic. It can
            only hold 25 parts, while Prosthetics can hold 50. Apparel has another configuration to it called
            Transparency, which dictates how transparent it will become when worn. Ranges from 0-1 from non-transparent
            to transparent. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Limb = "Left Arm";</li>
                            <li>Transparency = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Cloth</li>
                        <li>5 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="WedgeTemplate">WedgeTemplate</h2>
        <p style="font-family:Verdana">A triangular shaped template object. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Port">Port</h2>
        <p style="font-family:Verdana">An object used primarily in programming. Allows a microcontroller and computers
            to interact with their surroundings. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*3*3</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>PortID = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Silicon</li>
                        <li>2 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Sulfur">Sulfur</h2>
        <p style="font-family:Verdana">A yellow flammable solid. Being set on fire gives it a special blue fire. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1*7*1</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="RemoteControl">RemoteControl</h2>
        <p style="font-family:Verdana">Similar to an antenna, but sends trigger signals forward wirelessly when
            triggered. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 6</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>RemoteControlRange = 120;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 TriggerWire</li>
                        <li>1 Antenna</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RegionCloaker">RegionCloaker</h2>
        <p style="font-family:Verdana">Hides a certain region from players, making the coordinates not appear on their
            screen.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>500 Ruby</li>
                        <li>250 Iron</li>
                        <li>100 PowerCell</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Cooler">Cooler</h2>
        <p style="font-family:Verdana"> Cools down the heat around a space when supplied with power. Glows blue while
            functioning. Can be used to provide a cool environment in hot areas. Is also useful for cooling down objects
            such as iondrives and engines. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 16</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces -20
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Railgun">Railgun</h2>
        <p style="font-family:Verdana"> Fires a piercing rail at high speeds. A long range weapon. Requires rails and
            electricity for ammo. Damage increases for every 10 studs of length. Will pierce if the hit part is
            destroyed. Must be at least have a width and height of 6 and at least a length of 30 to function. While
            Railgun is similar to Artillery, the Railgun is nearly instant while Artillery is a projectile weapon.
            Requires to charge for one minute before it can fire. While charging and when charged, it creates large
            amount of heat. Charging status resets when this part is damaged. When it is finished charging, it will stop
            creating a sound. At that point, it must be triggered and supplied by a rail bin in order to fire. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8 * 40 * 8</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 170
                            heat when powered</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 150
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>30 Diamond</li>
                        <li>300 Titanium</li>
                        <li>1 Rail</li>
                        <li>50 Gun</li>
                        <li>60 Transformer</li>
                        <li>5 AlienCore</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Dispenser">Dispenser</h2>
        <p style="font-family:Verdana">Dispenses items from attached bins, similar to a faucet. Can also filter certain
            items from dispensing. Simply configure it to be a list of names. For example, "Copper Iron Wire"</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*8*2</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 0
                            Solid per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Filter = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Chute</li>
                        <li>1 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RustedMetal">RustedMetal</h2>
        <p style="font-family:Verdana">A weathered piece of metal.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25*25</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="FloatDevice">FloatDevice</h2>
        <p style="font-family:Verdana">Defies gravity when powered. Allows for vehicles such as space ships to float.
        </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 10
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Quartz</li>
                        <li>50 Wire</li>
                        <li>50 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Wing">Wing</h2>
        <p style="font-family:Verdana">Creates lift from being pushed forward. Works at higher altitudes and at better
            angles than a CrudeWing. Does not work in space or in non atmospheric planets.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*1*8</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Pipe</li>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Magnesium">Magnesium</h2>
        <p style="font-family:Verdana">A shiny gray solid that is flammable, randomly ignites when touching stone. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Flint">Flint</h2>
        <p style="font-family:Verdana">Useful for lighting up flammable materials. Simply rub it against a flammable
            material and it will set it on fire.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Wire">Wire</h2>
        <p style="font-family:Verdana">Allows electrical objects to interact with each other when connected by wires.
            For example, attaching a wire between a powercell and a light will allow electricity to move through the
            wire, allowing the light to function causing a source of light to be created.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 20*10</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Rifle">Rifle</h2>
        <p style="font-family:Verdana">A powerful long-range bolt action weapon. Q to scope. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Wood</li>
                        <li>150 Lead</li>
                        <li>100 Iron</li>
                        <li>5 Explosive</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Beacon">Beacon</h2>
        <p style="font-family:Verdana">Creates a small beacon of light when powered. When 'ShowOnMap\' is enabled, it
            broadcasts a signal into the universe. \'BeaconName\' changes the name of the beacon shown on the starmap.
            30 second cooldown for changing the configurables.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 15
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ShowOnMap = "false";</li>
                            <li>BeaconName = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Ruby</li>
                        <li>1 Jade</li>
                        <li>10 PowerCell</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Tire">Tire</h2>
        <p style="font-family:Verdana">A cylindrical shaped object used commonly in vehicles such as cars.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10*2</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Rubber</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="RBXScriptSignal">RBXScriptSignal</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Diamond">Diamond</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*3*3</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Hydroponic">Hydroponic</h2>
        <p style="font-family:Verdana">Grows grass and wood from water, turning attached water bins into either wood,
            sticks or grass. Incredibly useful for space bases or bases in areas devoid of life.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 5
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Grow = "Wood";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Wire</li>
                        <li>2 Cooler</li>
                        <li>20 Iron</li>
                        <li>2 Container</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DarkReactor">DarkReactor</h2>
        <p style="font-family:Verdana">Generates Dark Matter when powered and near a black hole. The reactor is very
            unstable, and if the reactor overheats it will cause a huge explosion. The DarkReactor generates up to 500
            degrees of temperature, meaing you will need atleast 25 coolers to cool the reactor to make sure it does not
            overheat. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">DarkReactor
                            generates around 1 DarkMatter</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Diamond</li>
                        <li>50 Titanium</li>
                        <li>100 Gold</li>
                        <li>10 AlienCore</li>
                        <li>5 Reactor</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Sail">Sail</h2>
        <p style="font-family:Verdana">Utilizes the wind to move forward. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 611</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Cloth</li>
                        <li>1 Stick</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Beryllium">Beryllium</h2>
        <p style="font-family:Verdana">A lightweight metal only found on Barren planets used for preventing plutonium
            cores from going supercritical until detonated.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 5*5*5</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="AirSupply">AirSupply</h2>
        <p style="font-family:Verdana">Generates a 300 stud radius oxygen bubble when powered on. Very important part
            for space ships, as it acts as the oxygen supply for the ship. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*4*3</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>20 Pipe</li>
                        <li>4 Motor</li>
                        <li>2 Container</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Constructor">Constructor</h2>
        <p style="font-family:Verdana"> Similar to an assembler, but constructs a model when triggered. However, the
            constructor must be supplied with the correct materials for a model. For example, a car model requiring 50
            iron and 30 wires will need a bin attached with 50 iron, a bin attached with 30 wires and 100 power. You can
            find out how many materials you need through the model loader gui. Has a 60 second cool down or a minute
            cooldown to prevent model spamming.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ModelCode = "";</li>
                            <li>Autolock = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Copper</li>
                        <li>5 Assembler</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="tinnitus">tinnitus</h2>
        <p style="font-family:Verdana">An interesting spring which does strange things. (unobtainable)</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="SteamTurbine">SteamTurbine</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 120
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">SteamTurbine
                            generates around 200 Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Pipe</li>
                        <li>20 Iron</li>
                        <li>5 Gear</li>
                        <li>3 Engine</li>
                        <li>10 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Neutronium">Neutronium</h2>
        <p style="font-family:Verdana">The most durable obtainable material in the game. It is a strange form of matter
            found from the crusts of neutron stars. Due to the nature of neutron stars, neutronium is the hardest known
            material as well as the densest known material in the universe.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*20*10</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Rotor">Rotor</h2>
        <p style="font-family:Verdana">Provides vertical height when spun, and only works in oxygen planets. The spin
            speed determines the height, and the tilt of the rotor determines the forward propulsion of the rotor. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>16 Copper</li>
                        <li>12 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Hydrogen">Hydrogen</h2>
        <p style="font-family:Verdana">A gas commonly found in stars and gas giants.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Radar">Radar</h2>
        <p style="font-family:Verdana">An instrument that shows a 2D top-down representation of Earth. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*20*25</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Iron</li>
                        <li>2 Antenna</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BurnerGenerator">BurnerGenerator</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">
                            BurnerGenerator generates around 6 Power</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Artillery">Artillery</h2>
        <p style="font-family:Verdana"> Fires a fast-moving metal shell upon being triggered. This metal shell generates
            a small explosion upon impact. Costs 10 iron per shot. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*25*3</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Rubber</li>
                        <li>8 Flint</li>
                        <li>8 Sulfur</li>
                        <li>24 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Framewire">Framewire</h2>
        <p style="font-family:Verdana">Enter the matrix</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200*1*20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 ExoticMatter</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="EnergyShield">EnergyShield</h2>
        <p style="font-family:Verdana"> Creates a bubble made of energy that protects it from energy based weapons such
            as Lasers and Plasma Cannons. An EnergyShield has a few sets of properties that you can fine tune to create
            a balanced shield. ShieldRadius - The size of the entire shield. This will exponentially consume more power
            the higher the radius is. RegenerationSpeed - On a scale from 1 to 10 on how fast the shield will
            regenerate. ShieldStrength - Scale from 1 to 10 on how much the shield can endure. RegenerationSpeed and
            ShieldStrength both combined can't be over 11. For example, a regeneration speed of 6 and a shield strength
            of 5 is possible. However, a regeneration speed of 10 and a shield strength of 10 isn't, as 10 + 10 > 11 A
            regeneration speed of 1 and a shield strength of 10 however is possible, since 11 = 11. Another benefit for
            energy shields is that it blocks all warhead explosions, whether inside the shield or outside. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>GetShieldHealth()</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ShieldRadius = 100;</li>
                            <li>RegenerationSpeed = 5;</li>
                            <li>ShieldStrength = 5;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>75 Quartz</li>
                        <li>50 Aluminum</li>
                        <li>90 Silicon</li>
                        <li>200 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="AlienCore">AlienCore</h2>
        <p style="font-family:Verdana">A mysterious piece of technology found in aliens. Although its precise function
            is unknown, it manages to be extremely useful in advanced technologies. Generally, the harder an alien is to
            defeat, the more alien cores it has. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="TouchSensor">TouchSensor</h2>
        <p style="font-family:Verdana">Sends trigger signals upon contact with another player or another object.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*5</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Button</li>
                        <li>2 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="SalvageLaser">SalvageLaser</h2>
        <p style="font-family:Verdana"> --Fires a concentraded beam of energy when powered, which is used to salvage
            unanchored and unattached objects. -- -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 50
                            heat when powered</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*4*4</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Laser</li>
                        <li>2 Scrapper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ImpulseCannon">ImpulseCannon</h2>
        <p style="font-family:Verdana">Blasts a harmless burst of energy which sends anything nearby soaring at a high
            velocity.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*2*2</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Gear</li>
                        <li>20 Rubber</li>
                        <li>20 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Beaker">Beaker</h2>
        <p style="font-family:Verdana"> A container for holding mixed chemicals. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Primer">Primer</h2>
        <p style="font-family:Verdana">A component used in crafting recipes for a few objects.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Wire</li>
                        <li>25 Titanium</li>
                        <li>100 Silicon</li>
                        <li>50 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Lava">Lava</h2>
        <p style="font-family:Verdana">A liquid used for fueling many devices such as rockets and engines.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Aerogel">Aerogel</h2>
        <p style="font-family:Verdana">An incredibly light material that is very fragile.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*2*10</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Silicon</li>
                        <li>1 Water</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Microphone">Microphone</h2>
        <p style="font-family:Verdana">Used in programming. Takes user's inputs.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*3*3</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Silicon</li>
                        <li>2 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Gold">Gold</h2>
        <p style="font-family:Verdana">A very valuable and stretchable material.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 7*10*20</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="ZapWire">ZapWire</h2>
        <p style="font-family:Verdana">Allows electrical objects to interact with each other when connected by wires. If
            a flammable object is touched, it will be lit on fire.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 PowerCell</li>
                        <li>1 Wire</li>
                        <li>1 Flint</li>
                        <li>1 TouchSensor</li>
                        <li>1 TriggerWire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DoorTemplate">DoorTemplate</h2>
        <p style="font-family:Verdana">When triggered, it will open, and if triggered again will close. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*20*2</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>DoorSwitch = "false";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="VintagePlasmaPistol">VintagePlasmaPistol</h2>
        <p style="font-family:Verdana">They don't make em like they used to.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>50 Aluminum</li>
                        <li>15 Uranium</li>
                        <li>20 Titanium</li>
                        <li>10 Jade</li>
                        <li>5 EnergyBomb</li>
                        <li>100 Plastic</li>
                        <li>1 EnergyGun</li>
                        <li>3 Gear</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BlackBox">BlackBox</h2>
        <p style="font-family:Verdana"> Records all activity in the region using very delicate instruments. Activates
            when locked and anchors to ensure accurate readings. ONLINE = Listening for event/Sharing event data, DATA =
            New data the owner hasn't seen. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>250 Antenna</li>
                        <li>75 Instrument</li>
                        <li>5 Diamond</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DevBattery">DevBattery</h2>
        <p style="font-family:Verdana">A debug item meant for developers.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1000000</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Sorter">Sorter</h2>
        <p style="font-family:Verdana"> --A device that sorts objects into their designated locations. --For example, if
            you configure the sorter to sort gold from the rest of the parts, --the sorter will move the gold to the
            right while other parts will move to the left. --This device is very useful in factory work, and is designed
            to organize items in factories. -- --The ObjectsToSort configuration can be formatted like "Gold" or "Gold,
            Aluminium, Wire, PowerCell". --Make sure to include the space infront of the comma. -- --The objects
            entering the sorter must be ungrounded and unanchored. --Requires power to function, and must be grounded or
            anchored. -- </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ObjectsToSort = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Quartz</li>
                        <li>2 Copper</li>
                        <li>2 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Modem">Modem</h2>
        <p style="font-family:Verdana">A computer networking object that allows you to send, save and get messages
            cross-region. This is an incredibly useful part to set up an internet of sorts and send data to other
            computers. The modem has 4 programmable functions to it. SendMessage(Data, NetworkId defaults to 0) sends a
            message (specifically through messaging service) carrying data. MessageSent is a special event that can be
            connected to via ConnectToEvent. Has one argument called Data which is the data received. PostRequest saves
            a string of data to the internet ':PostRequest(Domain, Data)' (modem must be locked) GetRequest gets a
            string of data from the internet ':GetRequest(Domain)' </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 10
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>PostRequest(Domain, PostData)</li>
                            <li>SendMessage(Data, ID)</li>
                            <li>GetRequest(Domain)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>NetworkID = 0;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>25 Wire</li>
                        <li>50 Quartz</li>
                        <li>1 Relay</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="TemperatureSensor">TemperatureSensor</h2>
        <p style="font-family:Verdana"> When the surrounding temperature goes out of a certain range, it will send
            trigger signals similar to a button. For example, if the current temperature is 160 and the temperature
            range is "40:140", then the sensor will send a signal. This is very useful for creating smart cooling
            systems for a vehicle or reactor, preventing overheating from occuring. If you want the temperature sensor
            to trigger within a certain range, simply reverse the range and have the greatest number first and least
            second. For example, "140:40" would trigger when the temperature is within that range. Connecting the
            TemperatureSensor to a reactor will use the reactor's temperature instead of the surrounding temperature.
        </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*8*1</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>TemperatureRange = "40:140";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Polysilicon</li>
                        <li>1 TriggerWire</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Refinery">Refinery</h2>
        <p style="font-family:Verdana">Turns oil into Petroleum and Gasoline. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 25
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Gear</li>
                        <li>40 Pipe</li>
                        <li>20 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Engine">Engine</h2>
        <p style="font-family:Verdana">It acts similar to a motor, but is powered by Oil instead of electricity. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 5
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 0.1
                            Gasoline per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>EngineSpeed = 10;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Iron</li>
                        <li>2 Pipe</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="GravityGenerator">GravityGenerator</h2>
        <p style="font-family:Verdana">Generates an artificial gravity field when powered on. The gravity field only
            affects players, not individual parts. The amount of gravity can also be configureed, but the more gravity
            the higher amount of power needed. Only works in space, not inside planets.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Gravity = 196.2;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>40 Quartz</li>
                        <li>20 Pipe</li>
                        <li>30 Engine</li>
                        <li>150 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="DataStoreService">DataStoreService</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Gyro">Gyro</h2>
        <p style="font-family:Verdana"> Stabilizes vehicles and structures by pointing upwards. Useful for mechs or
            orientating structures to the correct rotation. The gyro can also be configured to seek objects and players.
            When powered, the gyro will follow its seek commands that can be configured using hammer. The gyro has
            commands that allow it to find and seek objects and players. An example of gyro's seek configuration
            includes "Player1 Player2" which will seek and aim towards the nearest player. Putting "Radar" at the
            beginning of the seek configuration will make it target parts instead. For example, "Radar Gold Copper" will
            find the nearest Gold or Copper deposit. Putting "AllExcept" will make the seeker target everything except
            the given list, basically inverting it. For example, "AllExcept Player1 Player2" will target "Player3" or
            "Player"4 but not "Player1". The commands "Min" and "Max" set the minimum or maximum distance the seeker
            will target. For example, "Min20 Max500" will make the seeker only target objects within 500 studs and more
            than 20 studs away. TriggerWhenSeeked will trigger all connected parts every second when the Seek
            configurable is satisfied "TrigMin" and "TrigMax" work the same as "Min" and "Max" but it's for the trigger
            signal, trigger signal will only be sent if the above property is true. Putting "Sun" as part of the list
            will make the seeker automatically target the main stellar body in the system. Gyros also have a property
            called MaxTorque. This allows you to control the max force on the gyro to stabilize it. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>PointAt(PointPos)</li>
                        </ul>
                    </td>
                </tr>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>TriggerWhenSeeked = "false";</li>
                            <li>Seek = "";</li>
                            <li>DisableWhenUnpowered = "false";</li>
                            <li>MaxTorque = "100000000000, 100000000000, 100000000000";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Wire</li>
                        <li>8 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="WindTurbine">WindTurbine</h2>
        <p style="font-family:Verdana">Creates rotation using the wind. Unreliable and large motor. Does not work in
            space or no-atmosphere planets. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Wing</li>
                        <li>4 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="EnergySword">EnergySword</h2>
        <p style="font-family:Verdana">A short ranged melee weapon which forms its own gravitational field when lunged.
            Forged with incarnated ̶m̶a̶g̶i̶c science!</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Rubber</li>
                        <li>3 ZapWire</li>
                        <li>5 Titanium</li>
                        <li>1 DarkMatter</li>
                        <li>8 Ruby</li>
                        <li>1 Diamond</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Hotdog">Hotdog</h2>
        <p style="font-family:Verdana">sandwich.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Food</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Sign">Sign</h2>
        <p style="font-family:Verdana">Displays text or images. To display an image, configure it to id:imageid </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 40*20</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Font = "SciFi";</li>
                            <li>TextColor = "255, 255, 255";</li>
                            <li>SignText = "Text";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Cloth</li>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Katana">Katana</h2>
        <p style="font-family:Verdana">A weeaboo sword used to cut down your enemies. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Rubber</li>
                        <li>1 Stick</li>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="ConveyorBelt">ConveyorBelt</h2>
        <p style="font-family:Verdana">Moves objects ontop of it towards the front of the conveyor belt. Only moves when
            powered and anchored or attached to the ground. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 8*40</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 2
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>ConveyorBeltSpeed = 10;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>5 Gear</li>
                        <li>4 Rubber</li>
                        <li>3 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Chute">Chute</h2>
        <p style="font-family:Verdana">Is able to transfer solid parts between objects such as bins and extractors.
            **Contrary to popular belief, chutes can transfer more than one type of object.** **This means you can mix
            assemblers and extractors into the same system, no need for different chutes for each object. You can just
            make one long chute and connect your factory to it.** </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 200</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Solid"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Grass">Grass</h2>
        <p style="font-family:Verdana">An organic substance found in terra and forest planets. Often green, but can be
            other colors. Useful for planting seeds for agriculture.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25*25</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Shotgun">Shotgun</h2>
        <p style="font-family:Verdana"> Fires a shot of harmful pellets when triggered. Must be supplied with ammo in
            order to function. For example, you need an iron bin with 1 or more iron directly attached to it to work.
        </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 5*5*5</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>6 Sulfur</li>
                        <li>12 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Titanium">Titanium</h2>
        <p style="font-family:Verdana">A strong heavy material that is very useful for small scale constructs. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*25*15</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="DarkMatter">DarkMatter</h2>
        <p style="font-family:Verdana"> A very valuable material extracted from black holes and a few empty regions in
            space. Used primarily for weapons, but can also be convertred into energy and for other ingredients via
            DarkConverter. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Egg">Egg</h2>
        <p style="font-family:Verdana">The perfect consumable item.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Battery">Battery</h2>
        <p style="font-family:Verdana"> A light part that contains 400 energy and is prefilled. Can be refilled. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Sulfur</li>
                        <li>1 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="BasePart">BasePart</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Jade">Jade</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Oil">Oil</h2>
        <p style="font-family:Verdana">A liquid used in refineries to produce Gasoline which can be used for fueling
            engines and rockets and Petroleum which can be used to make plastic.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Keyboard">Keyboard</h2>
        <p style="font-family:Verdana">Similar to a button, except is programmable to take more than one key input. Can
            be attached to a vehicle seat or clicked by a player.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*5</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Programmable</td>
                    <td>
                        <ul>
                            <li>SimulateTextInput(Input, Player)</li>
                            <li>SimulateKeyPress(Key, Player)</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>10 Button</li>
                        <li>5 Silicon</li>
                        <li>4 Quartz</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Weld">Weld</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="ID">ID</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <div id="PartItem">
        <h2 id="Handle">Handle</h2>
        <p style="font-family:Verdana"> A handle which can be equipped when a player touches it, turning all connected
            parts into an equipable tool. Swing 0: Doesn't swing on click Swing 1: Swings downward on click Swing 2:
            Follows the mouse cursor TriggerMode 0: Trigger on mouse down TriggerMode 1: Trigger on mouse up TriggerMode
            2: Trigger on mouse down and mouse up If TriggerMode is set to anything else, it will trigger when the key
            TriggerMode is set to is pressed. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 2*2*2</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Swing = 1;</li>
                            <li>TriggerMode = 0;</li>
                            <li>ToolName = "Handle";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wood</li>
                        <li>2 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Relay">Relay</h2>
        <p style="font-family:Verdana"> A powerful transmitter capable of transmitting trigger signals and
            resources/power between different regions. It is a more powerful version of the antenna and transporter.
            Unlike the antenna, the relay has 2 modes, mode 0 and mode 1. Mode 0 sends resources/power and trigger
            signals, while mode 1 receives it. Unlike the antenna, it can also transfer power in inactive regions or
            regions without players in them. This means that you can connect a relay to your main base, warp away
            without anyone in the base, and still have the relay get the sufficient amount of power. However, you should
            have only one sending relay per coordinate, as conflicts can occur if there are 2 or more relays in the
            region/coordinates sending power or signals with the same ID. On the other hand, there can be an infinite
            number of receivers but the power/resources will be distributed evenly among them. For example, let's say a
            relay network has a total output of 500 power and 25 iron. If there are 5 active receivers, each of them
            will get 100 power and 5 iron. When the relay is red, it means it not functioning. When it turns green, it
            is properly linked up to another relay or is sending signals. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>LinkerID = 1;</li>
                            <li>Mode = 1;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>100 Quartz</li>
                        <li>5 Antenna</li>
                        <li>5 Transporter</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Button">Button</h2>
        <p style="font-family:Verdana">Sends trigger signals when clicked by a player. When connected to a seat and the
            input key is configured/configureed, the player sitting in the seat can activate the button by pressing the
            corresponding key. TriggerMode 0: Trigger on key down TriggerMode 1: Trigger on key up TriggerMode 2:
            Trigger on key down and key up</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 15*5</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>TriggerMode = 0;</li>
                            <li>KeyInput = "";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>1 Stone</li>
                        <li>1 Copper</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Bin">Bin</h2>
        <p style="font-family:Verdana"> Stores solid items such as Aluminum, Iron, Faucets, etc. Can store up to 1000
            items. When destroyed, every item inside will also be destroyed. The value increases as more items are added
            to it. Bins can also be used as crafting recipes, with the resources inside being used. You can configure
            this to disable crafting from the bin, by configuring the bin. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*4*4</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>CanBeCraftedFrom = "true";</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="GasTank">GasTank</h2>
        <p style="font-family:Verdana">A special type of container that only stores gases, but is able to store more.
            Can store up to 50k liquids.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>3 Rubber</li>
                        <li>5 Quartz</li>
                        <li>2 Container</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Uranium">Uranium</h2>
        <p style="font-family:Verdana">A radioactive material often found in deposits in planets, especially ones near
            stars. Useful for energy generation from reactors or radiation generators.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 1*3*1</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Copper">Copper</h2>
        <p style="font-family:Verdana">A brown shiny metal, the forefather of electronics. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 9*9*9</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Tile">Tile</h2>
        <p style="font-family:Verdana">A cheap material made from baked clay useful for building houses.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 10*10*10</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Stone</li>
                        <li>1 Rubber</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Plasma">Plasma</h2>
        <p style="font-family:Verdana">A gas found abundant in stars, and can be harvested from them. Used primarily for
            weapons, as well as electrical components.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="SMG">SMG</h2>
        <p style="font-family:Verdana">A fast firing, fully automatic gun able to pump out lots of rounds down range.
        </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>90 Rubber</li>
                        <li>140 Iron</li>
                        <li>3 Explosive</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Heatshield">Heatshield</h2>
        <p style="font-family:Verdana">Generates a 300 stud radius area that protects all players and **only players**
            within the vicinity from temperature damage.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 3
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>8 Heater</li>
                        <li>8 Cooler</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Rocket">Rocket</h2>
        <p style="font-family:Verdana">A propulsion device that consumes gasoline.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 60
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Temperature
                            Limit from -60 up to 200</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 10
                            Gasoline per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>Propulsion = 30;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>20 Engine</li>
                        <li>30 Pipe</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Turbofan">Turbofan</h2>
        <p style="font-family:Verdana">Generates thrust from crude Oil, similar to a Thruster. If a motor is attached to
            the front, it instead acts like an engine and rotates it. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 0.1
                            Oil per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <tr>
                    <td style="font-family:Verdana">Configurables</td>
                    <td>
                        <ul>
                            <li>TurboFanSpeed = 5;</li>
                        </ul>
                    </td>
                </tr>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>4 Wire</li>
                        <li>5 Pipe</li>
                        <li>4 Engine</li>
                        <li>5 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="NuclearWaste">NuclearWaste</h2>
        <p style="font-family:Verdana">A highly radioactive material produced from spent Uranium in a reactor.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Malleability:
                            Cannot be reshaped</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Charcoal">Charcoal</h2>
        <p style="font-family:Verdana">Similar to coal, and is created by burning sticks found from trees.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*3*3</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Heater">Heater</h2>
        <p style="font-family:Verdana">Generated heat when powered by electricity. Glows red hot while functioning. Can
            be used as insulation in cold environments.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 16</td>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Produces 10
                            heat when powered</td>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes 1
                            Power per second</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>2 Wire</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Sand">Sand</h2>
        <p style="font-family:Verdana">An abundant resource that can be found in the shores of terra and forest planets,
            the sea floors of ocean planets and in the dunes of desert planets. When burnt, the sand becomes glass.</p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 25*25*25</td>
                    <tr>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="Anchor">Anchor</h2>
        <p style="font-family:Verdana">When triggered or clicked, it is able to be anchored, a state in which it is
            immovable by physics, and applies to parts connected to it. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 4*4*4</td>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Consumes
                            Resource of Type "Trigger"</td>
                </tbody>
            </table>
        </figure>
        <table class="has-fixed-layout">
            <tbody>
                <td>Recipe</td>
                <td style="font-family:Verdana">
                    <ul>
                        <li>18 Iron</li>
                    </ul>
                </td>
            </tbody>
        </table>
    </div>
    <div id="PartItem">
        <h2 id="Silicon">Silicon</h2>
        <p style="font-family:Verdana">A metalloid that is very useful for electronics. </p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                    <tr>
                        <td class="has-text-align-center" data-align="center" style="font-family:Verdana">Has
                            Malleability of 3*4*3</td>
                </tbody>
            </table>
        </figure>
    </div>
    <div id="PartItem">
        <h2 id="MessagingService">MessagingService</h2>
        <p style="font-family:Verdana"></p>
        <hr
            class="wp-block-separator has-text-color has-background has-dark-gray-background-color has-dark-gray-color is-style-wide" />
        <figure class="wp-block-table is-style-stripes">
            <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background">
                <tbody>
    </div>
    <!-- SearchBar Functionality -->
    <script>
        function LookUp() {
            var Box = document.getElementById("TextBox");
            var Parts = document.getElementsByClassName("part");
            if (Parts !== null) {
                var Reg = new RegExp("(?=^|\\s)" + Box.value.toLowerCase());
                for (i = 0; i < Parts.length; i++) {
                    var name = Parts[i].firstElementChild.innerHTML.toLowerCase();
                    var HiddenAttr = document.createAttribute("hidden");
                    if (Reg.test(name)) {
                        if (Parts[i].attributes.getNamedItem("hidden") !== null) {
                            Parts[i].attributes.removeNamedItem("hidden");
                        }
                    } else {
                        if (Box.value == "") {
                            if (Parts[i].attributes.getNamedItem("hidden") !== null) {
                                Parts[i].attributes.removeNamedItem("hidden");
                            }
                        } else {
                            HiddenAttr.value = true;
                            Parts[i].attributes.setNamedItem(HiddenAttr);
                        }
                    }
                }
            }
        }
    </script>
</body>

</html>
