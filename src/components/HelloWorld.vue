<template>
  <div class="div-1">
    <!--  Tab components -->
    <nav class="navbar navbar-expand-lg">
      <div class="container-fluid">
        <a class="navbar-brand" href="https://wwww.jobstore.com.my">
          <img src="https://asset.jobstore.com/images/branding/jobstore_logo_blue.png" style="width: 50%;"
            alt="Jobstore.com Malaysia logo">
        </a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link" href="https://www.jobstore.com/my/browse-job">Browse Jobs</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.jobstore.com/my/companies">Companies</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.jobstore.com/my/download-app">Download App</a>
            </li>
          </ul>
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="https://www.jobstore.com/my/login/jobseeker">Sign In</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.jobstore.com/my/signup/jobseeker">Sign Up</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="https://www.jobstore.com/my/employer/index">
                <button class="btn btn-sm nav-custom-button" type="button">Employers</button>
              </a>
            </li>

          </ul>
        </div>
      </div>
    </nav>

    <!--  Search for Job -->
    <div class="container-box" style="margin-top: 40px; background-color:white;  height:500px; width: 100%;">
      <div class="grid-container">
        <div class="left-container" style="width: 80%;">
        </div>
        <div class="centre-container" style="width: 141%; margin-left: -21%;">
          <div class="title-section" style="color: #f8f8f8;">
            <h1 style="text-align: center;margin-top: 10%;font-size: 130%;font-weight: 700;">10,016 jobs available in
              <a href="https://www.jobstore.com/my/countries">
                <span style="color: white;text-decoration: underline;cursor: pointer;">Malaysia</span>
              </a>
            </h1>
          </div>
          <div class="search-container"
            style="background-color: #f8f8f8; border-radius: 10px; position: inherit;margin-top: 7%;margin-bottom: 9%;margin-left: 5%;margin-right: 5%;display: flex;align-items: center;height: 20%;flex-wrap: nowrap;align-content: stretch;justify-content: space-evenly;">
            <div class="search-box" style="display: flex; align-items: center;">
              <form method="GET" action="https://www.jobstore.com/my/search-jobs" accept-charset="UTF-8"
                style="display: flex; align-items: center;">

                <input type="text" name="keyword" class="search-keyword"
                  style="border: none; background: transparent; line-height: 3.85rem; font-size: 1.0rem; font-weight: 400; width: 200%;margin-left: -94px;"
                  placeholder="Search by job title or keyword" autocomplete="off">

                <span class="search-divider"
                  style="height: 40px; border-left: 1px solid #ddd;margin: 2px 5% 0px 2px;   margin-left: 10px;"></span>

                <input type="text" name="location" class="search-location"
                  style="border: none;background: transparent;line-height: 3.85rem;font-size: 1rem;font-weight: 400;width: 109%;margin-right: 20px;"
                  placeholder="Location or city" autocomplete="off">

                <div class="search-pin" id="" style="width: 23%;margin-right: -13%;">
                  <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                    <path fill-rule="evenodd"
                      d="M11.54 22.351l.07.04.028.016a.76.76 0 00.723 0l.028-.015.071-.041a16.975 16.975 0 001.144-.742 19.58 19.58 0 002.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 00-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 002.682 2.282 16.975 16.975 0 001.145.742zM12 13.5a3 3 0 100-6 3 3 0 000 6z"
                      clip-rule="evenodd" />
                  </svg>

                </div>
                <div class="search" id="" style="width: 70%;margin-right: -28%;padding-left: 20%;"><svg
                    xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                    <path d="M8.25 10.875a2.625 2.625 0 115.25 0 2.625 2.625 0 01-5.25 0z" />
                    <path fill-rule="evenodd"
                      d="M12 2.25c-5.385 0-9.75 4.365-9.75 9.75s4.365 9.75 9.75 9.75 9.75-4.365 9.75-9.75S17.385 2.25 12 2.25zm-1.125 4.5a4.125 4.125 0 102.338 7.524l2.007 2.006a.75.75 0 101.06-1.06l-2.006-2.007a4.125 4.125 0 00-3.399-6.463z"
                      clip-rule="evenodd" />
                  </svg>
                </div>

              </form>
            </div>
          </div>

          <div class="signbox"
            style="    line-height: 1rem;font-size: 0.85rem;color: #eee;vertical-align: middle;margin-top: 10%;">
            <img style="width: 5%;" src="https://assets.jobstore.com/images/index/icon/icon_user_in.png"
              alt="icon for Jobseeker Sign Up / Sign In">
            <a href="https://www.jobstore.com/my/login/jobseeker"
              style="color:white ; text-decoration: underline;margin-left: 3%;">Sign
              in&nbsp;</a><span>or</span>
            <a href="https://www.jobstore.com/my/signup/jobseeker"
              style="color:white ; text-decoration: underline;">&nbsp;Sign up</a> <span> to see your saved jobs on all
              your devices</span>
          </div>
        </div>
        <div class="right-container" style="width: 80%; margin-left: 20%;">
        </div>
      </div>
    </div>

    <!--  Trending Job -->
    <div class="container-box">
      <h2 style="margin-top: 100px;padding-bottom: 5%;"><b>Trending Jobs</b></h2>
        <swiper :modules="modules" :slides-per-view="3" :slides-per-group="3" :space-between="50" :navigation="false" :pagination="{ clickable: true, dynamicBullets: true }"
    :scrollbar="{ draggable: false, el: false }" :autoplay="{ delay: 2000, disableOnInteraction: false }" @swiper="onSwiper" @slideChange="onSlideChange">
        <swiper-slide>
          <!-- 1st pagination -->
          <div class="slide-container"  on-click="https://www.jobstore.com/my/post/3100315/head-of-investments-senior-manage">
            <small>KUALA LUMPUR</small><br>
            <b>Head of Investments (Senior Manager)</b><br>
            <a href="https://www.jobstore.com/my/post/3100315/head-of-investments-senior-manager">MYR16,000-MYR20,000
              (Monthly)</a><br>
            <div class="inline-container">
              <small>CRADLE FUND SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1230044/8uktYCR5hP/download.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container" onclick="ttps://www.jobstore.com/my/post/3319567/service-apartments-manager">
            <small>KUALA LUMPUR</small><br>
            <b>Service Apartments Manager</b><br>
            <a href="https://www.jobstore.com/my/post/3319567/service-apartments-manager">MYR12,000-MYR 15,000
              (Monthly)</a><br>
            <div class="inline-container">
              <small>GSH CORPORATION LIMITED</small>
              <img src="//asset.jobstore.com/uploads/image/862827/Dur9Mv4uB7/GSH.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>KUALA LUMPUR</small><br>
            <b>Backend Developer</b><br>
            <a
              href="https://www.jobstore.com/my/post/3100315/head-of-investments-senior-manager">MYR10,000-MYR15,000(Monthly)</a><br>
            <div class="inline-container">
              <small>JOBSTORE GROUP BHD</small>
              <img src="//asset.jobstore.com/uploads/image/40625/gh1dz1q6dd/jslinkedinicon.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <!-- 2nd pagination -->
        <swiper-slide>
          <div class="slide-container">
            <small>GEORGE TOWN</small><br>
            <b>Financial Advisor /Consultant</b><br>
            <a href="https://www.jobstore.com/my/post/3474083/financial-advisor-consultant">MYR9,000-MYR15,000
              (Monthly)</a><br>
            <div class="inline-container">
              <small>HON JEH GROUP</small>
              <img
                src="//assets.jobstore.com/uploads/image/1228976/5BPHKO9L4F/9595afa18d59a2a0d5cf9994b24aaa57674380-1.jpg"
                alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>KUALA LUMPUR</small><br>
            <b>Assistant Manager - Group Finance</b><br>
            <a
              href="https://www.jobstore.com/my/post/3305528/assistant-manager-group-finance">MYR8,500-MYR9,500(Monthly)</a><br>
            <div class="inline-container">
              <small>EDRA POWER HOLDINGS SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1261222/AkehTyrRpA/CGNEdraLogo2020Fullcolor.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>KUALA LUMPUR</small><br>
            <b>Operation Manager</b><br>
            <a href="https://www.jobstore.com/my/post/3076387/operation-manager">MYR8,000-MYR8,900(Monthly)</a><br>
            <div class="inline-container">
              <small>WEBHELP APAC</small>
              <img
                src="//asset.jobstore.com/uploads/image/828775/bdkWsZWyvP/71206952_2656578237726321_2885005089787871232_n.jpg"
                alt="">
            </div>
          </div>
        </swiper-slide>
        <!-- 3rd pagination -->
        <swiper-slide>
          <div class="slide-container">
            <small>JASIN</small><br>
            <b>Accountant</b><br>
            <a href="https://www.jobstore.com/my/post/2989475/accountant">MYR8,000-MYR10,000(Monthly)</a><br>
            <div class="inline-container">
              <small>HOMEWISE CONSTRUCTION (MELAKA) SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1248852/5FOsQAPofo/logohw.jpg" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>KUALA LUMPUR</small><br>
            <b>Membership Strategic Partnerships Manager</b><br>
            <a href="https://www.jobstore.com/my/post/2989475/accountant">MYR8,000-MYR10,000(Monthly)</a><br>
            <div class="inline-container">
              <small>BRITISH MALAYSIAN CHAMBER OF COMMERCE BERHAD</small>
              <img src="//asset.jobstore.com/uploads/image/5/lKdbU3e4Cz/logo_bmcoc.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>Telok Panglima Garang</small><br>
            <b>Sr.Manager/Manager Sales &amp; Marketing</b><br>
            <a
              href="https://www.jobstore.com/my/post/3133140/srmanagermanager-sales-marketing">MYR8,000-MYR14,000(Monthly)</a><br>
            <div class="inline-container">
              <small>VS Office Furniture (Malaysia) Sdn Bhd</small>
              <img src="//assets.jobstore.com/uploads/image/1239003/hKyrekoHjI/VS-LOGO-GREEN1.jpg" alt="">
            </div>
          </div>
        </swiper-slide>
        <!-- 4th pagination -->
        <swiper-slide>
          <div class="slide-container">
            <small>BUKIT MERTAJAM</small><br>
            <b>Finance Manager</b><br>
            <a href="https://www.jobstore.com/my/post/3354836/finance-manager"
              style="inline-size: auto;">MYR8,000-MYR10,000(Monthly)</a><br>
            <div class="inline-container">
              <small>CYTRON TECHNOLOGIES SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1269715/bnBST9nDNF/cytronlogo.jpg" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>PORT KLANG</small><br>
            <b>Sales Manager</b><br>
            <a href="https://www.jobstore.com/my/post/3354836/finance-manager">MYR8,000-MYR10,000(Monthly)</a><br>
            <div class="inline-container">
              <small>ZPMC ENGINEERING (MALAYSIA) SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1156420/7tuN1dy50Y/PP.JPG" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>PETALING JAYA</small><br>
            <b>Ecommerce Branding Manager</b><br>
            <a
              href="https://www.jobstore.com/my/post/3100848/ecommerce-branding-manager">MYR8,000-MYR11,000(Monthly)</a><br>
            <div class="inline-container">
              <small>BOXCUBE GROUP</small>
              <img src="//asset.jobstore.com/uploads/image/1107429/weNfFqAlOJ/BXCLogo2.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <!-- 5th pagination -->
        <swiper-slide>
          <div class="slide-container">
            <small>KUALA LUMPUR</small><br>
            <b>JJ1623KB Project Manager</b><br>
            <a
              href="https://www.jobstore.com/my/post/3095801/jj1623kb-project-manager">MYR8,000-MYR13,000(Monthly)</a><br>
            <div class="inline-container">
              <small>AGENSI PEKERJAAN SRM SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1269715/bnBST9nDNF/cytronlogo.jpg" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>PUCHONG</small><br>
            <b>Sales Consultant</b><br>
            <a
              href="https://www.jobstore.com/my/post/3095801/jj1623kb-project-manager">MYR8,000-MYR15,000(Monthly)</a><br>
            <div class="inline-container">
              <small>TIVOLLI DESIGN (M) SDN BHD</small>
              <img src="//assets.jobstore.com/uploads/image/1196094/tukgH8uMNQ/CompanyLogoBlack.jpeg" alt="">
            </div>
          </div>
        </swiper-slide>
        <swiper-slide>
          <div class="slide-container">
            <small>KUALA LUMPUR</small><br>
            <b>Manager, Fixed Income</b><br>
            <a href="https://www.jobstore.com/my/post/3438794/manager-fixed-income">MYR8,000-MYR11,000(Monthly)</a><br>
            <div class="inline-container">
              <small>PMB INVESTMENT BERHAD</small>
              <img src="//asset.jobstore.com/uploads/image/1201107/aCaEF1Hih7/LogoPelaburanMARA.png" alt="">
            </div>
          </div>
        </swiper-slide>
        <!-- <swiper-slide v-for="index in 6" :key="index">Slide {{ index }}</swiper-slide> -->
        
      </swiper>
      <div style="margin-top: 5%;">
        <span>
          <b><a href="https://www.jobstore.com/my/search-jobs"
              style="color: black; font-size: 0.8rem; padding-top: 2%;">View all trending jobs</a></b>
        </span>
      </div>

    </div>

    <!--  Popular Searches -->
    <div class="container-box">
      <h2 style="margin-top: 100px;"><b>Popular Searches</b></h2>
      <div class="paragraph-wrapper">
        <p>Popular Categories</p>
        <span>
          <a href="https://www.jobstore.com/my/browse/sales-marketing-job-vacancies">Sales / Marketing job</a>
          <a href="https://www.jobstore.com/my/browse/accounting-auditing-job-vacancies">Accounting / Auditing jobs</a>
          <a href="https://www.jobstore.com/my/browse/administrative-clerical-job-vacancies">Administrative / Clerical
            jobs</a>
          <a href="https://www.jobstore.com/my/browse/information-technology-job-vacancies">Information Technology
            jobs</a>
          <a href="https://www.jobstore.com/my/browse/engineering-job-vacancies">Engineering jobs</a>
          <a href="https://www.jobstore.com/my/browse/fb-tourism-hospitality-job-vacancies">F&B / Tourism / Hospitality
            jobs</a>
          <a href="https://www.jobstore.com/my/browse/customer-service-job-vacancies">Customer Service jobs</a>
          <a href="https://www.jobstore.com/my/search-jobs" style="color: black; font-size: 0.8rem;">View all
            categories</a>
        </span>


      </div>
      <div class="paragraph-wrapper">
        <p>Popular locations &nbsp;</p>
        <span>
          <a href="https://www.jobstore.com/my/search-jobs?location=Kuala+Lumpur">Kuala Lumpur</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Petaling+Jaya">Petaling Jaya</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Shah+Alam">Shah Alam</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Johor+Bahru">Puchong</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Johor+Bahru">Johor Bahru</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Subang+Jaya">Subang Jaya</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Seri+Kembangan">Klang</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Seri+Kembangan">Seri Kembangan</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Selangor">Selangor</a>
          <a href="https://www.jobstore.com/my/search-jobs?location=Ipoh">Ipoh</a>
          <a href="https://www.jobstore.com/my/search-jobs" style="color: black; font-size: 0.8rem;">View all
            categories</a>
        </span>
      </div>



    </div>

    <!--  Bottom  -->
    <div style="width: 100%; height:390px;background-color: #f8f8f8; margin-top: 100px;">
      <div class="container-box">
        <img src="https://asset.jobstore.com/images/branding/jobstore_logo_blue.png"
          style="margin-top: 50px; width: 23%;">
        <div class="row" style="justify-content: space-evenly; margin-top: 70px; text-align: left;">
          <div class="col-sm-4">
            <b style="color: #0704e1">COMPANY</b>
            <div style="color: black;">
              <a href="https://www.jobstore.com/my/company/about">About Us</a> <br>
              <a href="https://www.jobstore.com/my/support">Contact Support</a> <br>
              <a href="https://www.jobstore.com/my/company/career">Careers @ Jobstore</a> <br>
              <a href="https://www.jobstore.com/careers-blog/">Blog</a> <br>
              <a href="https://www.jobstore.com/my/employer/job">Partner Sites</a> <br>
              <a href="https://www.jobstore.com/my/fulfillment-policy">Fulfillment Policy</a>
            </div>
          </div>
          <div class="col-sm-4">
            <b style="color: #0704e1">JOBSEEKER</b>
            <div style="color: black;">
              <a href="https://www.jobstore.com/my/signup/jobseeker">Sign Up</a> <br>
              <a href="https://www.jobstore.com/my/login/jobseeker">Sign In</a> <br>
              <a href="https://www.jobstore.com/my/login/jobseeker">Check Applications</a> <br>
              <a href="https://www.jobstore.com/my/company/faq">Jobseeker FAQs</a> <br>
              <a href="https://www.jobstore.com/my/browse-job">Browse Jobs</a> <br>
              <a href="https://www.jobstore.com/my/browse-job-industry">Browse by Industry</a>
            </div>
          </div>
          <div class="col-sm-4">
            <b style="color: #0704e1">CONNECT WITH US</b>
            <div style="color: black;">
              <a href="https://www.facebook.com/jobstoredotcom?_rdr=p">Facebook</a> <br>
              <a href="https://twitter.com/i/flow/login?redirect_after_login=%2Fjobstoredotcom">Twitter</a> <br>
              <a href="https://www.linkedin.com/company/jobstore-com">LinkedIn</a> <br>
              <a href="https://www.instagram.com/jobstoredotcom/">Instagram</a> <br>
              <a href="https://www.jobstore.com/my#">Call us at +603 2716 5199</a>
              <br> <a href="https://www.jobstore.com/my/support">Send us a message</a>
            </div>
          </div>
        </div>

        <div>
          <div style="margin-top: 30px; font-size: 0.8rem; text-align: left; display: flex; align-items: center;">
            <div class="search-pin" id="" style="width: 2%;">
              <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-6 h-6">
                <path fill-rule="evenodd"
                  d="M11.54 22.351l.07.04.028.016a.76.76 0 00.723 0l.028-.015.071-.041a16.975 16.975 0 001.144-.742 19.58 19.58 0 002.683-2.282c1.944-1.99 3.963-4.98 3.963-8.827a8.25 8.25 0 00-16.5 0c0 3.846 2.02 6.837 3.963 8.827a19.58 19.58 0 002.682 2.282 16.975 16.975 0 001.145.742zM12 13.5a3 3 0 100-6 3 3 0 000 6z"
                  clip-rule="evenodd" />
              </svg>
            </div>
            <select v-model="selectedOption" style="border: none; background-color: #f8f8f8;">
              <option value="Malaysia">Malaysia</option>
              <option value="Singapore">Singapore</option>
              <option value="Hongkong">Hongkong</option>
              <option value="Philipines">Philipines</option>
              <option value="Indonesia">Indonesia</option>
              <option value="Thailand">Thailand</option>
              <option value="Vietnam">Vietnam</option>
              <option value="India">India</option>
              <option value="Australia">Australia</option>
              <option value="Japan">Japan</option>
              <option value="United Kingdom">United Kingdom</option>
              <option value="United States">United States</option>
            </select>
          </div>
          <div>
            <p style="margin-top: -15px; font-size: 0.8rem; text-align: right;">© 2023 Jobstore • Terms of Service •
              Privacy
              Policy • All Rights
              Reserved</p>
          </div>
        </div>



      </div>
    </div>
  </div>
</template>

<script>

// import { Swiper, SwiperSlide, Pagination } from 'swiper/vue';
// import 'swiper/css';
// import 'swiper/css/pagination';
  // import Swiper core and required modules
  import { Navigation, Pagination, Scrollbar, A11y, Autoplay } from 'swiper/modules';

  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';
  import 'swiper/css/navigation';
  import 'swiper/css/pagination';
  import 'swiper/css/scrollbar';


export default {
  data() {
    return {
      selectedOption: 'Malaysia'
    };
  },
  components: {
    Swiper,
    SwiperSlide,
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log('slide change');
    };
    return {
      onSwiper,
        onSlideChange,
        modules: [Navigation, Pagination, Scrollbar, A11y, Autoplay ],
    };
  },
};


</script>

<style>
.grid-container {
  display: grid;
  grid-template-columns: 68% 37%;
  gap: 10px;
  padding: 10px;
}

.grid-container>div {
  text-align: center;
  padding: 0px 0;
}

.item1 {
  grid-row: 1 / 3;
}

/* .div-1 {
  background-image: linear-gradient(rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.85)), url('https://assets.jobstore.com/images/index/index_left_2304041040.jpg');
  height: 100vh;
  width: 100%;
} */

.text-orange-color {
  color: #ffa800;
}

.nav-item .nav-link {
  display: inline-block;
  height: 110px;
  line-height: 110px;
  padding: 0 15px;
  font-weight: 700;
  color: #666;
}

.nav-item .nav-link:hover {
  color: black;
}

.nav-item .nav-custom-button {
  display: block;
  width: 150px;
  height: 35px;
  line-height: 26px;
  font-size: 0.85rem;
  font-weight: 500;
  color: #fff;
  text-align: center;
  font-family: 'Noto Sans', sans-serif;
  text-transform: uppercase;
  background: #0704e1;
  border: 2px solid #0704e1;
  border-radius: 25px;
  margin: 40px 0;
  float: right;
}

.nav-item .nav-custom-button:hover {
  color: #0704e1;
  background: #fff;
}


.container-box {
  width: 1000px;
  text-align: center;
  justify-content: center;
  align-items: center;
  display: block;
  margin: auto;
}

.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
  column-gap: 0px;
}

.left-container,
.centre-container,
.right-container {
  background-size: cover;
  background-repeat: no-repeat;
}

.left-container {
  height: 500px;
  width: 100%;
  background-image: url(https://assets.jobstore.com/images/index/index_left_2304041040.jpg);
}

.centre-container {
  height: 500px;
  width: 100%;
  background-color: #0704e1;
}

.right-container {
  height: 500px;
  width: 100%;
  background-image: url(https://assets.jobstore.com/images/index/index_right_2304041040.jpg);
}

.slider {
  width: 100%;
  overflow: hidden;
  white-space: nowrap;
}

.slide {
  display: inline-block;
  width: calc(100% / 3);
  box-sizing: border-box;
  padding: 10px;
  /* Additional styles for the slide */
}

.col-sm-4 div a {
  color: black;
}

.col-sm-4 div a:hover {
  color: #0704e1;
}

a:link {
  text-decoration: none;
}

a:hover {
  color: black;
}


.slide-container {
  background-color: white;
  padding: 20px;
  box-shadow: 0px 10px 15px 0px #eee;
  margin-left: 4%;
  text-align: left;
  margin-right: 4%;
  height: 200px;
  margin-bottom: 4%;
}

.slide-container a {
  font-size: small;
}
.container-box slide-container:hover
{
  background-color: white;
  padding: 20px;
  box-shadow: 10px 10px 15px 10px #efefefc2;
  margin-left: 4%;
  text-align: left;
  margin-right: 4%;
  height: 200px;
  margin-bottom: 4%;
}

.inline-container {
  display: flex;
  align-items: center;
}

.inline-container p {
  margin-right: 10px;
  white-space: nowrap;
  overflow: hidden;
  text-overflow: ellipsis;
}

.slide-container img {
  height: auto;
  width: 10%;
  max-width: 100%;
  margin-left: auto;
}

.slide-container small {
  display: block;
  line-height: 1.85rem;
  font-size: 0.7rem;
  font-weight: 300;
  color: #888;
  text-transform: uppercase;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
}


.paragraph-wrapper {
  display: flex;
  align-items: baseline;
  justify-content: space-between;
}

.paragraph-wrapper p {
  display: inline-block;
  white-space: nowrap;
  margin-right: 10px;
}

.paragraph-wrapper span {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  gap: 10px;
  margin-left: 10px;
  padding-top: 5%;
}
</style>

