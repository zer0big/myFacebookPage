<template>
  <div class="right">
    <span class="Opretprofil">Profile details please</span>
    <br />
    <span class="asap">It works quickly.</span>

    <input class="details" type="text" placeholder=" Firstname" style="width: 180px;" />
    <input class="details" type="text" placeholder=" Lastname" style="width: 180px;" />
    <br />
    <input class="details" type="text" placeholder=" Mobile number" style="width: 377px;" />
    <br />
    <input class="details" type="password" placeholder=" New password" style="width: 377px;" />

    <div class="dob">Date of Birth</div>
    <a href title="click for details">
      <i class="imgQ"></i>
    </a>

    <span>
      <select class="date" title="day">
        <option value="0">day</option>
        <option value="0">0</option>
        <option value="1">1</option>
        <option value="2">2</option>
        <option value="3">3</option>
        <option value="4">4</option>
        <option value="5">5</option>
        <option value="5">5</option>
        <option value="6">6</option>
        <option value="7">7</option>
        <option value="8">8</option>
        <option value="9">9</option>
        <option value="10">10</option>
        <option value="11">11</option>
        <option value="12">12</option>
        <option value="13">13</option>
        <option value="14">14</option>
        <option value="15">15</option>
        <option value="17">17</option>
        <option value="18">18</option>
        <option value="19">19</option>
        <option value="20">20</option>
        <option value="21">21</option>
        <option value="22">22</option>
        <option value="23">23</option>
        <option value="24">24</option>
        <option value="25">25</option>
        <option value="26">26</option>
        <option value="27">27</option>
        <option value="28">28</option>
        <option value="29">29</option>
        <option value="30">30</option>
        <option value="31">31</option>
      </select>
      <select class="date">
        <option value="January">January</option>
        <option value="Feb">February</option>
        <option value="march">March</option>
      </select>
      <select name="year" class="date">
        <option value="2019">2019</option>
        <option value="2018">2018</option>
        <option value="2017">2017</option>
      </select>
    </span>
    <br />
    <div class="sex">Køn</div>

    <div class="radiorow">
      <div class="equaldistanceradio">
        <input type="radio" /> Male
      </div>

      <div class="equaldistanceradio">
        <input type="radio" /> Female
      </div>

      <div class="equaldistanceradio">
        <input type="radio" /> Other
      </div>
    </div>
    <div class="legalinfo">
      <p>
        Hvis du klikker på Opret profil, accepterer du vores
        <a
          href="#"
          style="text-decoration: none"
        >vilkår</a> .
        Læs mere om, hvordan vi indsamler, bruger og deler dine oplysninger,
        i vores
        <a
          href="#"
          style="text-decoration: none; cursor: pointer"
        >datapolitik</a> og om, hvordan vi bruger cookies og lignende teknologi,
        i vores
        <a
          href="#"
          style="text-decoration: none"
        >politik om cookies</a> . Du vil muligvis modtage sms-notifikationer fra
        os og kan framelde dem når som helst.
      </p>
    </div>
    <div class="opretprofil">
      <button class="opretbutton">Opret profil</button>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.right {
  /* top: 5em; */
  background-color: #f2f4f8;
  position: absolute;
  width: 45%;
  right: 0;
  height: 100%;
  /* margin-top: 0em; */
}
.Opretprofil {
  margin: 0%;
  display: block;
  position: relative;
  left: 20px;
  color: black;
  font-size: 40px;
  font-weight: bold;
  line-height: 29px;
  margin-top: 30px;
  width: 450px;
  /* word-spacing: -1px; */
  font-family: Helvetica, Arial, sans-serif;
}
.asap {
  /* position: absolute; */
  font-family: Helvetica, Arial, sans-serif;
  left: 20px;
  display: block;
  position: relative;
  font-size: 20px;
}
.details {
  background-color: white;
  position: relative;
  border: 1px solid #bdc7d8;
  border-radius: 5px;
  font-size: 18px;
  font-weight: 400;

  padding-bottom: 8px;
  padding-top: 10px;
  margin: 6px;
  left: 15px;
}
.dob {
  position: relative;
  left: 20px;
  color: #90949c;
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 7px;
  margin-top: 12px;
}
.date {
  position: relative;
  left: 20px;
  border: 1px solid #bdc7d8;
  border-radius: 1px;
  font-size: 13px;
  height: 30px;
  padding: 5px;
  font-weight: 400;
  overflow: visible !important;
  margin: 0 0em 0 0;
}
.sex {
  position: relative;
  left: 20px;
  color: #90949c;
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 7px;
  margin-top: 12px;
}
.imgQ {
  background-image: url(https://facebook.com//rsrc.php/v3/ya/r/JV_KZvOFNb-.png);
  position: absolute;
  width: 100px;
  height: 520px;
  left: 10px;
  clip: rect(0px, 0px, 0px, 0px);
}

.equaldistanceradio {
  margin: 0 1.81em 0 0;
}

.radiorow {
  display: flex;
  flex-direction: row;
  margin: 0 0 3em 0;
  position: relative;
  left: 25px;
  color: #90949c;
  font-size: 16px;
  font-weight: bold;
  margin-bottom: 7px;
  margin-top: 12px;
}
.legalinfo {
  color: #777;

  text-decoration: none;
  font-size: 11px;
  width: 316px;
  margin-left: 20px;
  display: block;

  font-family: Arial, Helvetica, sans-serif;
  margin-top: 12px;
}
.opretbutton {
  font-size: 19px;
  font-weight: bold !important;
  font-family: "Freight Sans Bold", Helvetica, Arial, sans-serif !important;
  margin-left: 20px;
  margin-top: 10px;
  margin-bottom: 10px;
  min-width: 194px;
  padding: 7px 20px;
  text-align: center;
  background: linear-gradient(#67ae55, #578843);
  background-color: #69a74e;
  box-shadow: inset 0 1px 1px #a4e388;
  border-color: #3b6e22 #3b6e22 #2c5115;
  border: 1px solid;
  border-radius: 5px;
  color: #fff;
  cursor: pointer;
  display: inline-block;
  letter-spacing: 1px;
  position: relative;
  text-shadow: 0 1px 2px rgba(0, 0, 0, 0.5);
  line-height: 126%;
}
</style>
