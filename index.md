<!DOCTYPE html>
<html>
  <head>
    <meta http-equiv="content-type" content="text/html; charset=windows-1252">
    <script>
    	 function LookUp(){
        var Box = document.getElementById("TextBox");
        var Parts = document.getElementsByClassName("part");
        if(Parts !== null){
          var Reg   = new RegExp("(?=^|\\s)"+Box.value.toLowerCase());
          console.log(Parts[0].innerHTML);
          console.log(Reg);
          for(i=0; i < Parts.length; i++){
						 var name = Parts[i].firstElementChild.innerHTML.toLowerCase();
             var HiddenAttr = document.createAttribute("hidden");
             if(Reg.test(name)){
               if(Parts[i].attributes.getNamedItem("hidden") !== null){
               	Parts[i].attributes.removeNamedItem("hidden");
               }
             	 console.log(name+": "+Reg.test(name));
             }else{
               if(Box.value == ""){
                 	if(Parts[i].attributes.getNamedItem("hidden") !== null){
                    Parts[i].attributes.removeNamedItem("hidden");
                   }
               }else{
               		HiddenAttr.value = true;
							 		Parts[i].attributes.setNamedItem(HiddenAttr);
               }
             }
          }
        }
      }
    </script>
    <style>
    	/* Style the search box inside the navigation bar */
      .topnav input[type=search] {
        float: right;
        padding: 6px;
        border: none;
        margin-top: 8px;
        margin-right: 16px;
        font-size: 17px;
      }
/* When the screen is less than 600px wide, stack the links and the search field vertically instead of horizontally */
      @media screen and (max-width: 600px) {
        .topnav a, .topnav input[type=search] {
          float: none;
          display: block;
          text-align: left;
          width: 100%;
          margin: 0;
          padding: 14px;
        }
        .topnav input[type=search] {
          border: 1px solid #ccc;
        }
      }
    </style>
  </head>
  <body>
    <p> There are a total of 243 Parts </p>
    <div class="topnav"> <input id="TextBox" placeholder="Search.." onsearch="LookUp()" type="search"> </div>
    <table class="has-subtle-pale-blue-background-color has-fixed-layout has-background" style="border:0px">
      <tbody>
        <tr>
          <td>
            <ul>
              <li class="part"><a href="#Aerogel">Aerogel</a></li>
              <li class="part"><a href="#Airshield">Airshield</a></li>
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
              <li class="part"><a href="#Bank">Bank</a></li>
              <li class="part"><a href="#Battery">Battery</a></li>
              <li class="part"><a href="#Beacon">Beacon</a></li>
              <li class="part"><a href="#BeamRifle">BeamRifle</a></li>
              <li class="part"><a href="#Bin">Bin</a></li>
              <li class="part"><a href="#BlackBox">BlackBox</a></li>
              <li class="part"><a href="#BladeTemplate">BladeTemplate</a></li>
              <li class="part"><a href="#Boiler">Boiler</a></li>
              <li class="part"><a href="#Boombox">Boombox</a></li>
              <li class="part"><a href="#Brick">Brick</a></li>
              <li class="part"><a href="#BurnerGenerator">BurnerGenerator</a></li>
              <li class="part"><a href="#BurstLaser">BurstLaser</a></li>
              <li class="part"><a href="#Button">Button</a></li>
              <li class="part"><a href="#Cannon">Cannon</a></li>
              <li class="part"><a href="#Charcoal">Charcoal</a></li>
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
              <li class="part"><a href="#CornerTemplate">CornerTemplate</a></li>
              <li class="part"><a href="#CornerTetraTemplate">CornerTetraTemplate</a></li>
              <li class="part"><a href="#Coupler">Coupler</a></li>
              <li class="part"><a href="#CrudeWing">CrudeWing</a></li>
              <li class="part"><a href="#CylinderTemplate">CylinderTemplate</a></li>
              <li class="part"><a href="#DarkConverter">DarkConverter</a></li>
              <li class="part"><a href="#DarkMatter">DarkMatter</a></li>
              <li class="part"><a href="#DarkReactor">DarkReactor</a></li>
              <li class="part"><a href="#Decoupler">Decoupler</a></li>
              <li class="part"><a href="#DelayWire">DelayWire</a></li>
              <li class="part"><a href="#Deposit">Deposit</a></li>
              <li class="part"><a href="#DevBattery">DevBattery</a></li>
              <li class="part"><a href="#DevGenerator">DevGenerator</a></li>
              <li class="part"><a href="#Diamond">Diamond</a></li>
              <li class="part"><a href="#Disk">Disk</a></li>
              <li class="part"><a href="#Dispenser">Dispenser</a></li>
              <li class="part"><a href="#DoorTemplate">DoorTemplate</a></li>
            </ul>
          </td>
          <td>
            <ul>
              <li class="part"><a href="#DriveBox">DriveBox</a></li>
              <li class="part"><a href="#Egg">Egg</a></li>
              <li class="part"><a href="#ElectricFence">ElectricFence</a></li>
              <li class="part"><a href="#EnergyBomb">EnergyBomb</a></li>
              <li class="part"><a href="#EnergyGun">EnergyGun</a></li>
              <li class="part"><a href="#EnergyShield">EnergyShield</a></li>
              <li class="part"><a href="#Engine">Engine</a></li>
              <li class="part"><a href="#EthernetCable">EthernetCable</a></li>
              <li class="part"><a href="#ExoticMatter">ExoticMatter</a></li>
              <li class="part"><a href="#Explosive">Explosive</a></li>
              <li class="part"><a href="#Extractor">Extractor</a></li>
              <li class="part"><a href="#Faucet">Faucet</a></li>
              <li class="part"><a href="#Fence">Fence</a></li>
              <li class="part"><a href="#Filter">Filter</a></li>
              <li class="part"><a href="#FingerprintSensor">FingerprintSensor</a></li>
              <li class="part"><a href="#FireWood">FireWood</a></li>
              <li class="part"><a href="#Flint">Flint</a></li>
              <li class="part"><a href="#FloatDevice">FloatDevice</a></li>
              <li class="part"><a href="#FluidProjector">FluidProjector</a></li>
              <li class="part"><a href="#Food">Food</a></li>
              <li class="part"><a href="#Forcefield">Forcefield</a></li>
              <li class="part"><a href="#FrameWire">FrameWire</a></li>
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
              <li class="part"><a href="#Hatch">Hatch</a></li>
              <li class="part"><a href="#Heater">Heater</a></li>
              <li class="part"><a href="#Heatshield">Heatshield</a></li>
              <li class="part"><a href="#Helium">Helium</a></li>
              <li class="part"><a href="#Hotdog">Hotdog</a></li>
              <li class="part"><a href="#HttpService">HttpService</a></li>
              <li class="part"><a href="#HullTemplate">HullTemplate</a></li>
              <li class="part"><a href="#Hydrogen">Hydrogen</a></li>
              <li class="part"><a href="#Hydroponic">Hydroponic</a></li>
              <li class="part"><a href="#HyperDrive">HyperDrive</a></li>
              <li class="part"><a href="#Ice">Ice</a></li>
              <li class="part"><a href="#Instrument">Instrument</a></li>
              <li class="part"><a href="#IonDrive">IonDrive</a></li>
              <li class="part"><a href="#IonRocket">IonRocket</a></li>
              <li class="part"><a href="#Iron">Iron</a></li>
              <li class="part"><a href="#Jade">Jade</a></li>
              <li class="part"><a href="#Katana">Katana</a></li>
              <li class="part"><a href="#Keyboard">Keyboard</a></li>
              <li class="part"><a href="#Kiln">Kiln</a></li>
              <li class="part"><a href="#Laser">Laser</a></li>
              <li class="part"><a href="#Lava">Lava</a></li>
              <li class="part"><a href="#Lead">Lead</a></li>
              <li class="part"><a href="#LifeSensor">LifeSensor</a></li>
              <li class="part"><a href="#Light">Light</a></li>
              <li class="part"><a href="#LightBridge">LightBridge</a></li>
            </ul>
          </td>
          <td>
            <ul>
              <li class="part"><a href="#LiquidTank">LiquidTank</a></li>
              <li class="part"><a href="#Magnesium">Magnesium</a></li>
              <li class="part"><a href="#Marble">Marble</a></li>
              <li class="part"><a href="#Melter">Melter</a></li>
              <li class="part"><a href="#MessagingService">MessagingService</a></li>
              <li class="part"><a href="#Microcontroller">Microcontroller</a></li>
              <li class="part"><a href="#Microphone">Microphone</a></li>
              <li class="part"><a href="#MiningLaser">MiningLaser</a></li>
              <li class="part"><a href="#Mint">Mint</a></li>
              <li class="part"><a href="#Missile">Missile</a></li>
              <li class="part"><a href="#Modem">Modem</a></li>
              <li class="part"><a href="#ModemMessages">ModemMessages</a></li>
              <li class="part"><a href="#Motor">Motor</a></li>
              <li class="part"><a href="#MustardGas">MustardGas</a></li>
              <li class="part"><a href="#NeonBuildingPart">NeonBuildingPart</a></li>
              <li class="part"><a href="#Neutronium">Neutronium</a></li>
              <li class="part"><a href="#NightVisionGoggles">NightVisionGoggles</a></li>
              <li class="part"><a href="#NitrogenOxide">NitrogenOxide</a></li>
              <li class="part"><a href="#NuclearWaste">NuclearWaste</a></li>
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
              <li class="part"><a href="#Polysilicon">Polysilicon</a></li>
              <li class="part"><a href="#Port">Port</a></li>
              <li class="part"><a href="#PowerCell">PowerCell</a></li>
              <li class="part"><a href="#Propeller">Propeller</a></li>
              <li class="part"><a href="#Prosthetic">Prosthetic</a></li>
              <li class="part"><a href="#PsiSwitch">PsiSwitch</a></li>
              <li class="part"><a href="#Pulley">Pulley</a></li>
              <li class="part"><a href="#Pulverizer">Pulverizer</a></li>
              <li class="part"><a href="#Pump">Pump</a></li>
              <li class="part"><a href="#Quartz">Quartz</a></li>
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
              <li class="part"><a href="#Rifle">Rifle</a></li>
              <li class="part"><a href="#Rocket">Rocket</a></li>
              <li class="part"><a href="#Rotor">Rotor</a></li>
              <li class="part"><a href="#Rubber">Rubber</a></li>
              <li class="part"><a href="#Ruby">Ruby</a></li>
              <li class="part"><a href="#SMG">SMG</a></li>
              <li class="part"><a href="#Sail">Sail</a></li>
              <li class="part"><a href="#SalvageLaser">SalvageLaser</a></li>
              <li class="part"><a href="#Sand">Sand</a></li>
              <li class="part"><a href="#Scrapper">Scrapper</a></li>
              <li class="part"><a href="#Screen">Screen</a></li>
            </ul>
          </td>
          <td>
            <ul>
              <li class="part"><a href="#Seat">Seat</a></li>
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
              <li class="part"><a href="#SpotLight">SpotLight</a></li>
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
              <li class="part"><a href="#Torch">Torch</a></li>
              <li class="part"><a href="#TouchScreen">TouchScreen</a></li>
              <li class="part"><a href="#TouchTrigger">TouchTrigger</a></li>
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
              <li class="part"><a href="#WindTurbine">WindTurbine</a></li>
              <li class="part"><a href="#Wing">Wing</a></li>
              <li class="part"><a href="#Wire">Wire</a></li>
              <li class="part"><a href="#Wood">Wood</a></li>
              <li class="part"><a href="#ZapWire">ZapWire</a></li>
              <li class="part"><a href="#tinnitus">tinnitus</a></li>
            </ul>
          </td>
        </tr>
      </tbody>
    </table>
  </body>
</html>
