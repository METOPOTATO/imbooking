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

  .icon{
    width: 16px;
    height: 16px;
  }

  .icon-zalo {
    width: 18px;
    height: 18px;
  }


  .div-zalo{
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: row;
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

  .social-button {
      position: fixed;
      bottom: 20px;
      right: 20px;
      display: flex;
      flex-direction: column;
      gap: 10px;
  }

  .social-button a {
      display: inline-block;
      width: 50px;
      height: 50px;
      background-color: #0078FF; /* Màu xanh dương cho Zalo */
      border-radius: 50%;
      text-align: center;
      line-height: 50px;
      font-size: 20px;
      color: white;
      text-decoration: none;
      transition: background-color 0.3s;
  }

  .social-button a.facebook {
      background-color: #4267B2; /* Màu xanh Facebook */
  }

  /* Thêm hiệu ứng hover cho nút */
  .social-button a:hover {
      opacity: 0.8;
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
          <a href="https://m.me/620954641739050" target="_blank" class="btn messenger">
            <i class="fab fa-facebook-messenger"></i> Messenger
          </a>
        </li>
        <li class="menu-item">
          <a href="tel:02438803333" class="btn phone">
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
        <td><input type="text" placeholder="Tên của bạn *" bind:value={name}>
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
        <td><input type="tel" placeholder="Số điện thoại *" bind:value={phone}>
          {#if phoneError}
            <span style="color: red;">{phoneError}</span>
          {/if}
        </td>
        <td><Flatpickr class='date-picker' bind:value={dob} placeholder='Ngày sinh' altInput/></td>
  
      </tr>
      <tr>
        <td><input type="email" placeholder="Email" bind:value={email}></td>
        <td>
          <select id="country" name="country" bind:value={nation} class='date-picker'>
            <option value="Vietnam">Việt Nam</option>
            <option value="Korea">Korea</option>
            <option value="Afghanistan">Afghanistan</option>
            <option value="Albania">Albania</option>
            <option value="Algeria">Algeria</option>
            <option value="Andorra">Andorra</option>
            <option value="Angola">Angola</option>
            <option value="Antigua and Barbuda">Antigua and Barbuda</option>
            <option value="Argentina">Argentina</option>
            <option value="Armenia">Armenia</option>
            <option value="Australia">Australia</option>
            <option value="Austria">Austria</option>
            <option value="Azerbaijan">Azerbaijan</option>
            <option value="Bahamas">Bahamas</option>
            <option value="Bahrain">Bahrain</option>
            <option value="Bangladesh">Bangladesh</option>
            <option value="Barbados">Barbados</option>
            <option value="Belarus">Belarus</option>
            <option value="Belgium">Belgium</option>
            <option value="Belize">Belize</option>
            <option value="Benin">Benin</option>
            <option value="Bhutan">Bhutan</option>
            <option value="Bolivia">Bolivia</option>
            <option value="Bosnia and Herzegovina">Bosnia and Herzegovina</option>
            <option value="Botswana">Botswana</option>
            <option value="Brazil">Brazil</option>
            <option value="Brunei">Brunei</option>
            <option value="Bulgaria">Bulgaria</option>
            <option value="Burkina Faso">Burkina Faso</option>
            <option value="Burundi">Burundi</option>
            <option value="Côte d'Ivoire">Côte d'Ivoire</option>
            <option value="Cabo Verde">Cabo Verde</option>
            <option value="Cambodia">Cambodia</option>
            <option value="Cameroon">Cameroon</option>
            <option value="Canada">Canada</option>
            <option value="Central African Republic">Central African Republic</option>
            <option value="Chad">Chad</option>
            <option value="Chile">Chile</option>
            <option value="China">China</option>
            <option value="Colombia">Colombia</option>
            <option value="Comoros">Comoros</option>
            <option value="Congo (Congo-Brazzaville)">Congo (Congo-Brazzaville)</option>
            <option value="Costa Rica">Costa Rica</option>
            <option value="Croatia">Croatia</option>
            <option value="Cuba">Cuba</option>
            <option value="Cyprus">Cyprus</option>
            <option value="Czechia (Czech Republic)">Czechia (Czech Republic)</option>
            <option value="Democratic Republic of the Congo">Democratic Republic of the Congo</option>
            <option value="Denmark">Denmark</option>
            <option value="Djibouti">Djibouti</option>
            <option value="Dominica">Dominica</option>
            <option value="Dominican Republic">Dominican Republic</option>
            <option value="Ecuador">Ecuador</option>
            <option value="Egypt">Egypt</option>
            <option value="El Salvador">El Salvador</option>
            <option value="Equatorial Guinea">Equatorial Guinea</option>
            <option value="Eritrea">Eritrea</option>
            <option value="Estonia">Estonia</option>
            <option value="Eswatini (fmr. Swaziland)">Eswatini (fmr. Swaziland)</option>
            <option value="Ethiopia">Ethiopia</option>
            <option value="Fiji">Fiji</option>
            <option value="Finland">Finland</option>
            <option value="France">France</option>
            <option value="Gabon">Gabon</option>
            <option value="Gambia">Gambia</option>
            <option value="Georgia">Georgia</option>
            <option value="Germany">Germany</option>
            <option value="Ghana">Ghana</option>
            <option value="Greece">Greece</option>
            <option value="Grenada">Grenada</option>
            <option value="Guatemala">Guatemala</option>
            <option value="Guinea">Guinea</option>
            <option value="Guinea-Bissau">Guinea-Bissau</option>
            <option value="Guyana">Guyana</option>
            <option value="Haiti">Haiti</option>
            <option value="Holy See">Holy See</option>
            <option value="Honduras">Honduras</option>
            <option value="Hungary">Hungary</option>
            <option value="Iceland">Iceland</option>
            <option value="India">India</option>
            <option value="Indonesia">Indonesia</option>
            <option value="Iran">Iran</option>
            <option value="Iraq">Iraq</option>
            <option value="Ireland">Ireland</option>
            <option value="Israel">Israel</option>
            <option value="Italy">Italy</option>
            <option value="Jamaica">Jamaica</option>
            <option value="Japan">Japan</option>
            <option value="Jordan">Jordan</option>
            <option value="Kazakhstan">Kazakhstan</option>
            <option value="Kenya">Kenya</option>
            <option value="Kiribati">Kiribati</option>
            <option value="Kuwait">Kuwait</option>
            <option value="Kyrgyzstan">Kyrgyzstan</option>
            <option value="Laos">Laos</option>
            <option value="Latvia">Latvia</option>
            <option value="Lebanon">Lebanon</option>
            <option value="Lesotho">Lesotho</option>
            <option value="Liberia">Liberia</option>
            <option value="Libya">Libya</option>
            <option value="Liechtenstein">Liechtenstein</option>
            <option value="Lithuania">Lithuania</option>
            <option value="Luxembourg">Luxembourg</option>
            <option value="Madagascar">Madagascar</option>
            <option value="Malawi">Malawi</option>
            <option value="Malaysia">Malaysia</option>
            <option value="Maldives">Maldives</option>
            <option value="Mali">Mali</option>
            <option value="Malta">Malta</option>
            <option value="Marshall Islands">Marshall Islands</option>
            <option value="Mauritania">Mauritania</option>
            <option value="Mauritius">Mauritius</option>
            <option value="Mexico">Mexico</option>
            <option value="Micronesia">Micronesia</option>
            <option value="Moldova">Moldova</option>
            <option value="Monaco">Monaco</option>
            <option value="Mongolia">Mongolia</option>
            <option value="Montenegro">Montenegro</option>
            <option value="Morocco">Morocco</option>
            <option value="Mozambique">Mozambique</option>
            <option value="Myanmar (formerly Burma)">Myanmar (formerly Burma)</option>
            <option value="Namibia">Namibia</option>
            <option value="Nauru">Nauru</option>
            <option value="Nepal">Nepal</option>
            <option value="Netherlands">Netherlands</option>
            <option value="New Zealand">New Zealand</option>
            <option value="Nicaragua">Nicaragua</option>
            <option value="Niger">Niger</option>
            <option value="Nigeria">Nigeria</option>
            <option value="North Korea">North Korea</option>
            <option value="North Macedonia">North Macedonia</option>
            <option value="Norway">Norway</option>
            <option value="Oman">Oman</option>
            <option value="Pakistan">Pakistan</option>
            <option value="Palau">Palau</option>
            <option value="Palestine State">Palestine State</option>
            <option value="Panama">Panama</option>
            <option value="Papua New Guinea">Papua New Guinea</option>
            <option value="Paraguay">Paraguay</option>
            <option value="Peru">Peru</option>
            <option value="Philippines">Philippines</option>
            <option value="Poland">Poland</option>
            <option value="Portugal">Portugal</option>
            <option value="Qatar">Qatar</option>
            <option value="Romania">Romania</option>
            <option value="Russia">Russia</option>
            <option value="Rwanda">Rwanda</option>
            <option value="Saint Kitts and Nevis">Saint Kitts and Nevis</option>
            <option value="Saint Lucia">Saint Lucia</option>
            <option value="Saint Vincent and the Grenadines">Saint Vincent and the Grenadines</option>
            <option value="Samoa">Samoa</option>
            <option value="San Marino">San Marino</option>
            <option value="Sao Tome and Principe">Sao Tome and Principe</option>
            <option value="Saudi Arabia">Saudi Arabia</option>
            <option value="Senegal">Senegal</option>
            <option value="Serbia">Serbia</option>
            <option value="Seychelles">Seychelles</option>
            <option value="Sierra Leone">Sierra Leone</option>
            <option value="Singapore">Singapore</option>
            <option value="Slovakia">Slovakia</option>
            <option value="Slovenia">Slovenia</option>
            <option value="Solomon Islands">Solomon Islands</option>
            <option value="Somalia">Somalia</option>
            <option value="South Africa">South Africa</option>
            
            <option value="South Sudan">South Sudan</option>
            <option value="Spain">Spain</option>
            <option value="Sri Lanka">Sri Lanka</option>
            <option value="Sudan">Sudan</option>
            <option value="Suriname">Suriname</option>
            <option value="Sweden">Sweden</option>
            <option value="Switzerland">Switzerland</option>
            <option value="Syria">Syria</option>
            <option value="Tajikistan">Tajikistan</option>
            <option value="Tanzania">Tanzania</option>
            <option value="Thailand">Thailand</option>
            <option value="Timor-Leste">Timor-Leste</option>
            <option value="Togo">Togo</option>
            <option value="Tonga">Tonga</option>
            <option value="Trinidad and Tobago">Trinidad and Tobago</option>
            <option value="Tunisia">Tunisia</option>
            <option value="Turkey">Turkey</option>
            <option value="Turkmenistan">Turkmenistan</option>
            <option value="Tuvalu">Tuvalu</option>
            <option value="Uganda">Uganda</option>
            <option value="Ukraine">Ukraine</option>
            <option value="United Arab Emirates">United Arab Emirates</option>
            <option value="United Kingdom">United Kingdom</option>
            <option value="United States of America">United States of America</option>
            <option value="Uruguay">Uruguay</option>
            <option value="Uzbekistan">Uzbekistan</option>
            <option value="Vanuatu">Vanuatu</option>
            <option value="Venezuela">Venezuela</option>
            
            <option value="Yemen">Yemen</option>
            <option value="Zambia">Zambia</option>
            <option value="Zimbabwe">Zimbabwe</option>
        </select>
        
          <!-- <input type="text" placeholder="Quốc tịch" bind:value={nation}> -->
        </td>
      </tr>
      <tr>
        <td colspan="2"><input type="text" placeholder="Địa chỉ" bind:value={address}></td>
      </tr>
      <tr>
        <td colspan="2">
          <select id="department"  bind:value={depart}>
            <option value="" disabled selected>Chọn Khoa</option>
            <option value="2">Khoa Nội</option>
            <option value="surgery">Khoa Ngoại</option>
            <option value="5">Khoa Tai Mũi Họng</option>
            <option value="12">Khoa Khoa Mắt</option>
            <option value="6">Khoa Da Liễu </option>
            <option value="8">Khoa Răng</option>
            <option value="10">Khoa Vaccine</option>
            <option value="9">Khoa Sản</option>
            <option value="9">Khoa Khám sức khỏe</option>
          </select>
        </td>
      </tr>
      <tr>
        <td>
          <Flatpickr bind:value={date} placeholder='Ngày khám' class='date-picker'/>
          <!-- <Datepicker bind:selected={date} /> -->
        </td>
        <td>
          
          <select id="appointment-time"  bind:value={time} placeholder='thoi gian'>
            <option value="08:00">08:00 AM</option>
            <option value="08:15">08:15 AM</option>
            <option value="08:30">08:30 AM</option>
            <option value="08:45">08:45 AM</option>
            <option value="09:00">09:00 AM</option>
            <option value="09:15">09:15 AM</option>
            <option value="09:30">09:30 AM</option>
            <option value="09:45">09:45 AM</option>
            <option value="10:00">10:00 AM</option>
            <option value="10:15">10:15 AM</option>
            <option value="10:30">10:30 AM</option>
            <option value="10:45">10:45 AM</option>
            <option value="11:00">11:00 AM</option>
            <option value="11:15">11:15 AM</option>
            <option value="11:30">11:30 AM</option>
            <option value="11:45">11:45 AM</option>
            <option value="12:00">12:00 PM</option>
            <option value="12:15">12:15 PM</option>
            <option value="12:30">12:30 PM</option>
            <option value="12:45">12:45 PM</option>
            <option value="13:00">01:00 PM</option>
            <option value="13:15">01:15 PM</option>
            <option value="13:30">01:30 PM</option>
            <option value="13:45">01:45 PM</option>
            <option value="14:00">02:00 PM</option>
            <option value="14:15">02:15 PM</option>
            <option value="14:30">02:30 PM</option>
            <option value="14:45">02:45 PM</option>
            <option value="15:00">03:00 PM</option>
            <option value="15:15">03:15 PM</option>
            <option value="15:30">03:30 PM</option>
            <option value="15:45">03:45 PM</option>
            <option value="16:00">04:00 PM</option>
            <option value="16:15">04:15 PM</option>
            <option value="16:30">04:30 PM</option>
            <option value="16:45">04:45 PM</option>
            <option value="17:00">05:00 PM</option>
            <option value="17:15">05:15 PM</option>
            <option value="17:30">05:30 PM</option>
            <option value="17:45">05:45 PM</option>
            <option value="18:00">06:00 PM</option>
            <option value="18:15">06:15 PM</option>
            <option value="18:30">06:30 PM</option>
            <option value="18:45">06:45 PM</option>
            <option value="19:00">07:00 PM</option>
            <option value="19:15">07:15 PM</option>
            <option value="19:30">07:30 PM</option>
            <option value="19:45">07:45 PM</option>
            <option value="20:00">08:00 PM</option>
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

<div class="social-button">
  <!-- Nút Zalo -->
  <a href="https://zalo.me/1076574194805497139" target="_blank" class="a-zalo">
    <div class="div-zalo">
      <img src="images/zalo.png" alt="Zalo Icon" class="icon-zalo"/>
    </div>
  </a>
  <!-- Nút Facebook -->
  <a href="https://m.me/620954641739050" class="facebook" target="_blank" title="Chat with Facebook"><i class="fab fa-facebook-messenger"></i></a>
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
  import Flatpickr from 'svelte-flatpickr';

  import 'flatpickr/dist/flatpickr.css'
  import './custom.css';
  // import DatePicker from 'svelte-date-picker'
  import { fade } from 'svelte/transition';
  let name = '';
  let gender = 'male';
  let phone = '';
  let dob = '';
  let email = '';
  let nation = 'Vietnam';
  let address = '';
  let depart = '';
  let date = '';
  let time = '08:00';
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

    const response = fetch("https://pkimedicare.1s2haven.com/booking/", {
      method: "POST",
      headers: {
        'Content-Type': 'application/json',
        // 'X-CSRFToken': getCookie('csrftoken'),
        // 'Access-Control-Allow-Headers': 'Content-Type',
        // 'Access-Control-Allow-Origin': '*'
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