<template>
  <!-- <h1 class="text-3xl font-bold underline">Hello world!</h1> -->

  <form>
    <label class="block">
      <img class="mb-10" src="../assets/Login-logo.png" />
      <ul>
        <li>
          <input type="text" placeholder="Username" class="username input" />
        </li>
        <!-- Using form state modifers, the classes can be identical for every input -->
        <li>
          <input type="password" placeholder="NIK" class="password input" />
        </li>
        <!-- Using form state modifers, the classes can be identical for every input -->
        <li class="mt-8">
          <a class="text-style" href="#">Forgot Password?</a>
        </li>
        <li>
          <button class="Btn-login">Login</button>
        </li>
        <li>
          <div
            class="kotak p-6 max-w-sm mx-auto rounded-xl shadow-lg flex items-center space-x-4"
          >
            <p class="textnya">
              Untuk Login harus menggunakan PIN Karyawan Untuk mengganti PIN,
              dapat melalui link Reset PIN Apabila user belum terdaftar, hubungi
              IT Dev
            </p>
          </div>
        </li>
      </ul>
      <br/>
      <caption class="capt">
        Alfagift - 2022.03.24
      </caption>
    </label>
    <!-- ... -->
  </form>
</template>

<script>
export default {};
</script>

<style scoped>
.capt {
    margin-top: 39px;
  width: 139px;
  height: 20px;
  left: 686px;
  top: 820px;

  font-weight: 400;
  font-size: 14px;
  line-height: 20px;

  color: #073d5d;
}
.textnya {
  width: 396px;
  height: 67px;
  left: 559px;
  top: 702px;
  font-family: sans-serif;
  font-style: normal;
  font-weight: 500;
  font-size: 15px;
  line-height: 18px;
  text-align: center;

  color: #505050;
}
.kotak {
  margin-top: 39px;
  background: #dedede;
}
.input {
  height: 56px;
  width: 453px;
  left: 530px;
  top: 339px;
  padding: 20px;
  border-radius: 10px;
  background: #dedede;
  margin-top: 39px;
}
.text-style {
  width: 158.48px;
  height: 21.05px;
  left: 677px;
  top: 521px;
  font-weight: 500;
  font-size: 15px;
  line-height: 18px;
  text-align: center;
  color: #f46d3d;
}
.Btn-login {
  margin-top: 20px;
  width: 453px;
  height: 56px;
  left: 530px;
  top: 569px;
  background: #f46d3d;
  box-shadow: 0px 3px 10px rgba(0, 0, 0, 0.15);
  border-radius: 10px;
  color: #dedede;
}
.cardo {
  width: 453px;
  height: 115px;
  left: 530px;
  top: 678px;
  background: #dedede;
  border-radius: 10px;
}
</style>
