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
      <swiper :modules="modules" :slides-per-view="3" :slides-per-group="3" :space-between="50" :navigation="false"
        :pagination="{ clickable: true, dynamicBullets: true }" :scrollbar="{ draggable: false, el: false }"
        :autoplay="{ delay: 3000, disableOnInteraction: false }" @swiper="onSwiper" @slideChange="onSlideChange">
        <swiper-slide>
          <!-- 1st pagination -->
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3100315/head-of-investments-senior-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3319567/service-apartments-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3100315/head-of-investments-senior-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3474083/financial-advisor-consultant'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3305528/assistant-manager-group-finance'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3076387/operation-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/2989475/accountant'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/2989475/accountant'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3133140/srmanagermanager-sales-marketing'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3354836/finance-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3354836/finance-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3100848/ecommerce-branding-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3095801/jj1623kb-project-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3095801/jj1623kb-project-manager'">
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
          <div class="slide-container"
            onclick="window.location.href='https://www.jobstore.com/my/post/3438794/manager-fixed-income'">
            <small>KUALA LUMPUR</small><br>
            <b>Manager, Fixed Income</b><br>
            <a href="https://www.jobstore.com/my/post/3438794/manager-fixed-income">MYR8,000-MYR11,000(Monthly)</a><br>
            <div class="inline-container">
              <small>PMB INVESTMENT BERHAD</small>
              <img src="//asset.jobstore.com/uploads/image/1201107/aCaEF1Hih7/LogoPelaburanMARA.png" alt="">
            </div>
          </div>
        </swiper-slide>
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

    <!--  Detail company -->
    <div style="width: 100%; height:415px;background-color: #f8f8f8; margin-top: 100px;">
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
              <a href="https://www.facebook.com/jobstoredotcom?_rdr=p"><svg xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 30 30" width="30px" height="30px">
                  <path
                    d="M15,3C8.373,3,3,8.373,3,15c0,6.016,4.432,10.984,10.206,11.852V18.18h-2.969v-3.154h2.969v-2.099c0-3.475,1.693-5,4.581-5 c1.383,0,2.115,0.103,2.461,0.149v2.753h-1.97c-1.226,0-1.654,1.163-1.654,2.473v1.724h3.593L19.73,18.18h-3.106v8.697 C22.481,26.083,27,21.075,27,15C27,8.373,21.627,3,15,3z" />
                </svg>Facebook</a> <br>

              <a href="https://twitter.com/i/flow/login?redirect_after_login=%2Fjobstoredotcom">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 50 50" width="30px" height="30px">
                  <path
                    d="M 50.0625 10.4375 C 48.214844 11.257813 46.234375 11.808594 44.152344 12.058594 C 46.277344 10.785156 47.910156 8.769531 48.675781 6.371094 C 46.691406 7.546875 44.484375 8.402344 42.144531 8.863281 C 40.269531 6.863281 37.597656 5.617188 34.640625 5.617188 C 28.960938 5.617188 24.355469 10.21875 24.355469 15.898438 C 24.355469 16.703125 24.449219 17.488281 24.625 18.242188 C 16.078125 17.8125 8.503906 13.71875 3.429688 7.496094 C 2.542969 9.019531 2.039063 10.785156 2.039063 12.667969 C 2.039063 16.234375 3.851563 19.382813 6.613281 21.230469 C 4.925781 21.175781 3.339844 20.710938 1.953125 19.941406 C 1.953125 19.984375 1.953125 20.027344 1.953125 20.070313 C 1.953125 25.054688 5.5 29.207031 10.199219 30.15625 C 9.339844 30.390625 8.429688 30.515625 7.492188 30.515625 C 6.828125 30.515625 6.183594 30.453125 5.554688 30.328125 C 6.867188 34.410156 10.664063 37.390625 15.160156 37.472656 C 11.644531 40.230469 7.210938 41.871094 2.390625 41.871094 C 1.558594 41.871094 0.742188 41.824219 -0.0585938 41.726563 C 4.488281 44.648438 9.894531 46.347656 15.703125 46.347656 C 34.617188 46.347656 44.960938 30.679688 44.960938 17.09375 C 44.960938 16.648438 44.949219 16.199219 44.933594 15.761719 C 46.941406 14.3125 48.683594 12.5 50.0625 10.4375 Z" />
                </svg>Twitter</a> <br>

              <a href="https://www.linkedin.com/company/jobstore-com">
                <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 30 30" width="30px" height="30px">
                  <path
                    d="M24,4H6C4.895,4,4,4.895,4,6v18c0,1.105,0.895,2,2,2h18c1.105,0,2-0.895,2-2V6C26,4.895,25.105,4,24,4z M10.954,22h-2.95 v-9.492h2.95V22z M9.449,11.151c-0.951,0-1.72-0.771-1.72-1.72c0-0.949,0.77-1.719,1.72-1.719c0.948,0,1.719,0.771,1.719,1.719 C11.168,10.38,10.397,11.151,9.449,11.151z M22.004,22h-2.948v-4.616c0-1.101-0.02-2.517-1.533-2.517 c-1.535,0-1.771,1.199-1.771,2.437V22h-2.948v-9.492h2.83v1.297h0.04c0.394-0.746,1.356-1.533,2.791-1.533 c2.987,0,3.539,1.966,3.539,4.522V22z" />
                </svg>LinkedIn</a><br>
              <a href="https://www.instagram.com/jobstoredotcom/"><svg xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 30 30" width="30px" height="30px">
                  <path
                    d="M 9.9980469 3 C 6.1390469 3 3 6.1419531 3 10.001953 L 3 20.001953 C 3 23.860953 6.1419531 27 10.001953 27 L 20.001953 27 C 23.860953 27 27 23.858047 27 19.998047 L 27 9.9980469 C 27 6.1390469 23.858047 3 19.998047 3 L 9.9980469 3 z M 22 7 C 22.552 7 23 7.448 23 8 C 23 8.552 22.552 9 22 9 C 21.448 9 21 8.552 21 8 C 21 7.448 21.448 7 22 7 z M 15 9 C 18.309 9 21 11.691 21 15 C 21 18.309 18.309 21 15 21 C 11.691 21 9 18.309 9 15 C 9 11.691 11.691 9 15 9 z M 15 11 A 4 4 0 0 0 11 15 A 4 4 0 0 0 15 19 A 4 4 0 0 0 19 15 A 4 4 0 0 0 15 11 z" />
                </svg>
                Instagram</a> <br>
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
      modules: [Navigation, Pagination, Scrollbar, A11y, Autoplay],
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

.container-box slide-container:hover {
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

