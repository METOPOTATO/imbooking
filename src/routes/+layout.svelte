<style>

  .top{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 50px;
  }

  .address{
    width: 70%;
    display: flex;
    flex-direction: row;
    right: 0px;
    /* background-color: #7beba6; */
    margin-top: 5px;
  }

  .phone-c{
    width: 70%;
    display: flex;
    flex-direction: row;
    margin-top: 5px;
  }

  header{
    display: flex;
    flex-direction: row;
    height: 130px;
    justify-content: center;
    align-items: center;
    background-color: #eafaff;
  }

  header .container{
    height: 100px;
    width: 80%;
    display: flex;
    flex-direction: row;
    justify-content: space-around;

  }

  .container .logo{
    /* background-color: #1bb682; */
    height: 100px;
  }
  
  .container .logo img{
    height: 150px;
  }

  .container .contact{
    display: flex;
    flex-direction: row;
  }
  
  .logo{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
  }
  
  .logo .title h1{
    margin-left: 10px;
  }

  .contact .menu {
    list-style: none;
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 0;
    padding: 0;
  }

  .contact .menu-item {
    margin: 0 10px;
  }

  .contact .btn {
    display: inline-block;
    padding: 10px 20px;
    color: #fff;
    text-decoration: none;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }

  .contact .zalo {
    background-color: #0084ff;
  }

  .contact .messenger {
    background-color: #0078ff;
  }

  .contact .phone {
    background-color: #25d366;
  }

  .contact .btn:hover {
    opacity: 0.8;
  }

  .content{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }

  .content .title h1{
    text-transform: uppercase;
    margin: 15px 0;
  }

  .content .img{
    display: flex;
    justify-content: center;
    
  }

  .content .img img{
    width: 70%;
  }

  .btn i, .btn .icon {
    margin-right: 8px;
    vertical-align: middle;
  }

  .icon {
    width: 16px;
    height: 16px;
  }


  /* for input */
  .appointment-table {
    width: 100%;
    max-width: 800px;
    margin: 0 auto;
    border-spacing: 20px; /* Khoảng cách giữa các ô */
    width: 800px;

  }

  table td {
    padding: 10px;
    vertical-align: top;
  }

  input[type="text"],
  input[type="tel"],
  input[type="email"],
  input[type="date"],
  select,
  textarea {
    width: 100%;
    padding: 10px;
    border-top: 0px;
    border-bottom: 0px;
    border: 1px solid #ccc;
    border-radius: 4px;
    box-sizing: border-box;
  }

  textarea {
    resize: vertical; /* Cho phép người dùng điều chỉnh chiều cao của textarea */
  }

  .gender-radio input[type="radio"] {
    margin-right: 5px;
  }

  .gender-radio label {
    margin-right: 15px;
  }

  .input{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-bottom: 20px;
  }

  /* .container2{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    margin-bottom: 20px;
    border: 1px solid black;
    width: 800px;
  } */

  .submit{
    width: 50px;
  }

  .submit button{
    background-color: #7beba6;
    border-radius: 10px;
    padding: 10px  10px 10px 10px;
    border: 1px #e7fff0;
  }

  @media screen and (max-width: 800px) {
    header{
      display: flex;
      flex-direction: column;
      justify-content: center;
      text-align: center;
      height: auto;
      width: auto;
    }

    header .container{
      height: auto;
      width: auto;
      display: flex;
      flex-direction: column;
    }

    .logo{
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
    }

    .contact .btn {
      padding: 5px 10px;
    }

    .content h1{
      text-align: center;
      font-size: 25px;
    }

    .content .img img{
      width: 100%;
    }

    .input{
      margin: 0px;
      width: auto;
    }

    table td {
      padding: 0px;
    }

    .appointment-table {
      border-spacing: 10px; /* Khoảng cách giữa các ô */
      width: auto;
    }

    .top{
      height: auto;
    }

    .address{
      width: 100%;
      /* flex-direction: row; */
    }
    .phone-c{
      display: flex;
      width: 100%;
      left: 0px;
      margin-left: 0px;
      padding-left: 0px;

      flex-direction: row;
    }
  }
</style>


<div class="top">
  <div class="address">
    <i class="fa-solid fa-location-dot"></i> TTTM The Garden, khu đô thị, Đ. Mễ Trì, Mỹ Đình, Nam Từ Liêm, Hà Nội     
  </div>
  <div class="phone-c">
    <i class="fa-solid fa-phone"></i>Số điện thoại: 024.3880.3333
  </div>
</div>

<header>
  <div class="container">
    <div class="logo">
      <img src="images/logo2.png" alt="logo">
    </div>
    <div class="contact">
      <ul class="menu">
        <li class="menu-item">
          <a href="https://zalo.me/1076574194805497139" target="_blank" class="btn zalo">
            <img src="images/zalo.png" alt="Zalo Icon" class="icon" /> Zalo
          </a>
        </li>
        <li class="menu-item">
          <a href="m.me/620954641739050" target="_blank" class="btn messenger">
            <i class="fab fa-facebook-messenger"></i> Messenger
          </a>
        </li>
        <li class="menu-item">
          <a href="tel:123456789" class="btn phone">
            <i class="fas fa-phone-alt"></i> Phone
          </a>
        </li>
      </ul>
  </div>

</header>


<div class="content">
  <div class="title">
    <h1>đặt lịch hẹn khám bệnh</h1>
  </div>
  <div class="img">
      <img src="/images/banner2.png" alt="">
  </div>
</div>

<div class="input">
  <div>
    <table class="appointment-table">
      <tr>
        <td><input type="text" placeholder="Tên của bạn" bind:value={name}>
          {#if nameError}
            <span style="color: red;">{nameError}</span>
          {/if}
        </td>
        <td>
          <div class="gender-radio">
            <input type="radio" id="male" name="gender" value="male" bind:group={gender}>
            <label for="male">Nam</label>
            
            <input type="radio" id="female" name="gender" value="female" bind:group={gender}>
            <label for="female">Nữ</label>
            
          </div>
        </td>
      </tr>
      <tr>
        <td><input type="tel" placeholder="Số điện thoại" bind:value={phone}>
          {#if phoneError}
            <span style="color: red;">{phoneError}</span>
          {/if}
        </td>
        <td><input type="text" placeholder="Ngày sinh" bind:value={dob}></td>
  
      </tr>
      <tr>
        <td><input type="email" placeholder="Email" bind:value={email}></td>
        <td><input type="text" placeholder="Quốc tịch" bind:value={nation}></td>
      </tr>
      <tr>
        <td colspan="2"><input type="text" placeholder="Địa chỉ" bind:value={address}></td>
      </tr>
      <tr>
        <td colspan="2">
          <select id="department"  bind:value={depart}>
            <option value="" disabled selected>Chọn Khoa</option>
            <option value="general">Khoa Nội</option>
            <option value="surgery">Khoa Ngoại</option>
            <option value="pediatrics">Khoa Tai Mũi Họng</option>
            <option value="cardiology">Khoa Khoa Mắt</option>
            <option value="cardiology">Khoa Liễu </option>
            <option value="dental">Khoa Răng</option>
            <option value="vaccine">Khoa Vaccine</option>
            <option value="obgyn">Khoa Sản</option>
          </select>
        </td>
      </tr>
      <tr>
        <td>
          <input type="date" id="appointment-date" placeholder="Ngày khám"  bind:value={date}>
        </td>
        <td>
          <select id="appointment-time"  bind:value={time}>
            <option value="" disabled selected>Chọn Thời gian</option>
          </select>
        </td>
      </tr>
      <tr>
        <td colspan="2">
          <textarea placeholder="Mô tả triệu chứng" rows="4"  bind:value={symptom}></textarea>
        </td>
      </tr>
    </table>

  </div>

  <div class="submit">
    <button type="submit" on:click={postData}>Submit</button>
  </div>
</div>

{#if message}
  <div 
    transition:fade 
    class:error={isError} 
    class:success={!isError}
  >
    {message}
  </div>
{/if}

<footer>

</footer>

<script>
  import { fade } from 'svelte/transition';
  let name = '';
  let gender = 'male';
  let phone = '';
  let dob = '';
  let email = '';
  let nation = '';
  let address = '';
  let depart = '';
  let date = '';
  let time = '';
  let symptom = '';

  let nameError = '';
  let phoneError = '';

  let message = '';
  let isError = false;

  function validate(){
    let isValid = true;
    const pattern = /^\d{10,13}$/;

    if (!name) {
      nameError = 'Vui lòng nhập tên của bạn';
      isValid = false;
    } else {
      nameError = '';
    }

    if (!phone) {
      phoneError = 'Vui lòng nhập số điện thoại';
      isValid = false;
    } else if(!pattern.test(phone)) {
      phoneError = 'Số điện thoại phải có từ 10 đến 13 chữ số';
      isValid = false;
    }else{
      phoneError = '';
    }

    return isValid;
  }

  function getCookie(name) {
    let cookieValue = null;
    if (document.cookie && document.cookie !== '') {
      const cookies = document.cookie.split(';');
      for (let i = 0; i < cookies.length; i++) {
        const cookie = cookies[i].trim();
        if (cookie.substring(0, name.length + 1) === (name + '=')) {
          cookieValue = decodeURIComponent(cookie.substring(name.length + 1));
          break;
        }
      }
    }
    return cookieValue;
  }

  async function postData() {

    if (!validate()) {
      return; 
    }

    const response = fetch("http://127.0.0.1:9090/booking/", {
      method: "POST",
      headers: {
        'Content-Type': 'application/json',
        'X-CSRFToken': getCookie('csrftoken')
      },
      body: JSON.stringify({ name, gender, phone, dob, email, nation, address, depart, date, time, symptom }),

    })

    if (!response) {
      message = 'Thông tin được gửi chưa thành công, vui lòng thử lại';
    }else{
      alert('Chúng tôi đã tiếp nhận thông tin');
      isError = false;
      message = 'Data submitted successfully!';
    }
    

    

    setTimeout(() => {
      message = '';
    }, 5000);
  }
</script>


<slot></slot>