<!DOCTYPE html>
<html>
<body>

<h1>My Profile</h1>
<img src="https://github.com/PracoyoAdiNugroho/AlterraRepo/assets/50276930/d55c55f6-9ec1-424b-a5b4-9839a07067f4
" alt="Foto Diri" />
<!-- Mohon Maaf tidak bisa mengerjakan maximal karena terkendala laptop trouble, jadi hanya menggunakan HP saja -->
<h2>Informasi Pribadi</h2>
<p>Mohon Maaf tidak bisa mengerjakan maximal karena terkendala laptop trouble, jadi hanya menggunakan HP saja</p>
<p>Nama: Pracoyo Adi Nugroho</p>
<p>Alamat: Malang</p>
<p>Tanggal Lahir: 08 Juni 1988</p>
<p>Nomor Telepon: 081234673zzz</p>

<div class="mb-3">
  <label for="formInput1" class="form-label">Nama Depan</label>
  <input type="text" class="form-control" id="formId1" placeholder="Masukkan Nama Depan Anda">
</div>
<div class="mb-3">
  <label for="formInput2" class="form-label">Nama Belakang</label>
  <input type="text" class="form-control" id="formId2" placeholder="Masukkan Nama Belakang">
</div>
<form>
  <label for="fname">Name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lsaran">Saran:</label><br>
  <input type="text" id="lsaran" name="lsaran">
</form>
<form>
  <p>
  <label>Fahrenheit</label>
  <input id="inputFahrenheit" type="number" placeholder="Fahrenheit"
  oninput="temperatureConverter(this.value)"
  onchange="temperatureConverter(this.value)">
</p>
<p>Celsius: <span id="outputCelsius"></span></p>

</body>
</html>


</form>
function temperatureConverter(valNum) {
  valNum = parseFloat(valNum);
  document.getElementById("outputCelsius").innerHTML = (valNum-32) / 1.8;
}
