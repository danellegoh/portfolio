<template>
  <main>
    <!-- Experience Section -->
    <div>
      <div class="container mainbox">
        <h2 class="content1">Experiences</h2>
        <a class="content2 link" target="_blank" href="https://www.linkedin.com/in/danelle-goh/">View my LinkedIn profile for more details</a>
      </div>

      <!-- Keppel Internship -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/keppel.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <a class="content1 link" target="_blank" href="https://www.keppel.com/en/">Keppel Limited</a>
            <p class="content2">Enterprise Application Intern</p>
            <p class="content2">Jan 2024 - Aug 2024</p>
            <p class="content4">Coordinated annual User Access Review and supported daily operations for multiple applications, including SAP, Electronic Invoicing System, Service Request Tool and Treasury Management System.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/mssql.png">
              <img class="skillLogo" src="../assets/html.png">
              <img class="skillLogo" src="../assets/javascript.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="keppelLogo"
        companyLink="https://www.keppel.com/en/"
        projectName="Keppel Limited"
        title="Enterprise Application Intern"
        startDate="Jan 2024"
        endDate="Aug 2024"
        description="Coordinated annual User Access Review and supported daily operations for multiple applications, including SAP, Electronic Invoicing System, Service Request Tool and Treasury Management System. Management of tickets was done on ServiceNow and SharePoint."
        :skillLogos="[mssqlLogo, htmlLogo, javascriptLogo]" />
      
    </div>

    <!-- Technical Projects Section -->
    <div style="margin-top: 30px">
      <div class="container mainbox">
        <h2 class="content1">Technical Projects</h2>
        <a class="content2 link" target="_blank" href="https://github.com/danellegoh">View my GitHub here</a>
      </div>

      <!-- Portfolio -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/laptop.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <p class="content1">Portfolio</p>
            <p class="content2">Personal Project</p>
            <p class="content2">Jan 2024 - Present</p>
            <p class="content4">Ongoing personal project to showcase what I have worked on previously.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/html.png">
              <img class="skillLogo" src="../assets/javascript.png">
              <img class="skillLogo" src="../assets/css.png">
              <img class="skillLogo" src="../assets/bootstrap.png">
              <img class="skillLogo" src="../assets/vue.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="laptopLogo"
        companyLink="https://danellegoh.netlify.app/"
        projectName="Portfolio"
        title="Personal Project"
        startDate="Jan 2024"
        endDate="Present"
        description="Ongoing personal project to showcase what I have worked on previously."
        :skillLogos="[htmlLogo, javascriptLogo, cssLogo, bootstrapLogo, vueLogo]" />

      <!-- FYP Healthier Gen Z -->
      <project
        :projectLogo="h365Logo"
        companyLink="https://h365.vercel.app/"
        projectName="Healthy 365 Prototype for Youth"
        title="Final Year Project"
        startDate="Aug 2024"
        endDate="Nov 2024"
        description="Capstone project in collaboration with the Health Promotion Board (HPB), to create an improved version of H365 targeted at youth aged 13 to 17 years old, offering a gamified experience with non-monetary rewards."
        :skillLogos="[pythonLogo, flaskLogo, postgresqlLogo, javascriptLogo, vueLogo]" />

      <!-- IS442 Timperio CRM -->
      <project
        :projectLogo="timperioLogo"
        projectName="Customer Relationship Management (CRM) System"
        title="Object Oriented Programming | School Project"
        startDate="Aug 2024"
        endDate="Nov 2024"
        description="The web application enables efficient visualisation of customer purchase histories and personalised marketing efforts. It also aims to enhance customer engagement, improve sales performance, and streamline the management of customer data."
        :skillLogos="[javaLogo, springbootLogo, postgresqlLogo, typescriptLogo, reactLogo]" /> 
      
      <!-- IS216 Life Below Water -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/lifebelowwater.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <p class="content1">Life Below Water</p>
            <p class="content2">Web Application Development | School Project</p>
            <p class="content2">Aug 2023 - Nov 2023</p>
            <p class="content4">A web application aimed at increasing awareness and promoting action for marine conservation. It includes an interactive map, latest news, donation and volunteer pages, as well as a fun personality quiz.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/html.png">
              <img class="skillLogo" src="../assets/javascript.png">
              <img class="skillLogo" src="../assets/css.png">
              <img class="skillLogo" src="../assets/bootstrap.png">
              <img class="skillLogo" src="../assets/vue.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="lifeBelowWaterLogo"
        projectName="Life Below Water"
        title="Web Application Development | School Project"
        startDate="Aug 2023"
        endDate="Nov 2023"
        description="A web application aimed at increasing awareness and promoting action for marine conservation. It includes an interactive map, latest news, donation and volunteer pages, as well as a fun personality quiz."
        :skillLogos="[htmlLogo, javascriptLogo, cssLogo, bootstrapLogo, vueLogo]" />

      <!-- IS212 All in One -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/allinone.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <p class="content1">All in One - Skill-Based Portal</p>
            <p class="content2">Software Project Management | School Project</p>
            <p class="content2">Aug 2023 - Nov 2023</p>
            <p class="content4">Agile-managed project using scrum methodology. The application improves job application process within the organisation – for applicants, managers and HR.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/javascript.png">
              <img class="skillLogo" src="../assets/python.png">
              <img class="skillLogo" src="../assets/flask.png">
              <img class="skillLogo" src="../assets/mysql.png">
              <img class="skillLogo" src="../assets/vue.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="allInOneLogo"
        projectName="All in One - Skill-Based Portal"
        title="Software Project Management | School Project"
        startDate="Aug 2023"
        endDate="Nov 2023"
        description="Agile-managed project using scrum methodology. The application improves job application process within the organisation – for applicants, managers and HR."
        :skillLogos="[pythonLogo, flaskLogo, mysqlLogo, javascriptLogo, vueLogo]" />

      <!-- IS213 EcoPal -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/ecopal.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <p class="content1">EcoPal</p>
            <p class="content2">Enterprise Solution Development | School Project</p>
            <p class="content2">Jan 2023 - Apr 2023</p>
            <p class="content4">A web application to promote environmental sustainability, by reducing the use of single-use plastic bags through incentivisation and community-building.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/javascript.png">
              <img class="skillLogo" src="../assets/python.png">
              <img class="skillLogo" src="../assets/flask.png">
              <img class="skillLogo" src="../assets/mysql.png">
              <img class="skillLogo" src="../assets/rabbitmq.png">
              <img class="skillLogo" src="../assets/docker.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="ecopalLogo"
        projectName="EcoPal"
        title="Enterprise Solution Development | School Project"
        startDate="Jan 2023"
        endDate="Apr 2023"
        description="A web application to promote environmental sustainability, by reducing the use of single-use plastic bags through incentivisation and community-building."
        :skillLogos="[pythonLogo, flaskLogo, mysqlLogo, rabbitmqLogo, dockerLogo, javascriptLogo]" />

    </div>

    <!-- Other Projects Section -->
    <div style="margin-top: 30px; margin-bottom: 50px">
      <div class="container mainbox">
        <h2 class="content1">Other Projects</h2>
        <p class="content2">Analytics & Non-Technical Projects</p>
      </div>

      <!-- IS446 Timperio -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/timperio.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <a class="content1 link" target="_blank" href="https://drive.google.com/file/d/1NBBqMygcb-pjqLFG1ZKe4ESlPmYYXJ2R/view?usp=sharing">Timperio Case Study</a>
            <p class="content2">Managing Customer Relations with Analytics | School Project</p>
            <p class="content2">Oct 2023 - Nov 2023</p>
            <p class="content4">Provided an executive recommendation to improve Timperio's customer success strategy for the digital-online shopper, including creation of Tableau dashboard and mapping of customer journey.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/tableau.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="timperioLogo"
        companyLink="https://drive.google.com/file/d/1NBBqMygcb-pjqLFG1ZKe4ESlPmYYXJ2R/view?usp=sharing"
        projectName="Timperio Case Study"
        title="Managing Customer Relations with Analytics | School Project"
        startDate="Oct 2023"
        endDate="Nov 2023"
        description="Provided an executive recommendation to improve Timperio's customer success strategy for the digital-online shopper, including creation of Tableau dashboard and mapping of customer journey."
        :skillLogos="[tableauLogo]" />

      <!-- IS211 SMUG -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/smug.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <p class="content1">SMUG - eLearn Mobile Companion</p>
            <p class="content2">Interaction Design & Prototyping | School Project</p>
            <p class="content2">Aug 2022 - Nov 2022</p>
            <p class="content4">Prototype of a mobile application to notify users of upcoming academic deadlines and keep track of relevant course materials. Includes gamification aimed at improving effectiveness of study sessions.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/figma.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="smugLogo"
        projectName="SMUG - eLearn Mobile Companion"
        title="Interaction Design & Prototyping | School Project"
        startDate="Aug 2022"
        endDate="Nov 2022"
        description="Prototype of a mobile application to notify users of upcoming academic deadlines and keep track of relevant course materials. Includes gamification aimed at improving effectiveness of study sessions."
        :skillLogos="[figmaLogo]" />

      <!-- SMT203 Marijuana -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/sentimentanalysis.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <p class="content1">Sentiment Analysis of Legalising Recreational Marijuana in America</p>
            <p class="content2">Computational Social Science | School Project</p>
            <p class="content2">Aug 2022 - Nov 2022</p>
            <p class="content4">Analysed online sentiments from Twitter and Reddit using relevant APIs, breaking down into general and state-specific analysis. Conducted VADER, text, log-odds, and empath analysis.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/python.png">
              <img class="skillLogo" src="../assets/twitter.png">
              <img class="skillLogo" src="../assets/reddit.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="sentimentAnalysisLogo"
        projectName="Sentiment Analysis of Legalising Recreational Marijuana in America"
        title="Computational Social Science | School Project"
        startDate="Aug 2022"
        endDate="Nov 2022"
        description="Analysed online sentiments from Twitter and Reddit using relevant APIs, breaking down into general and state-specific analysis. Conducted VADER, text, log-odds, and empath analysis."
        :skillLogos="[pythonLogo, twitterLogo, redditLogo]" />

      <!-- COR1305 PV -->
      <!-- <div class="container box">
        <div class="row align-items-center justify-content-center">
          <div class="col-lg-1 col-md-2 col-sm-3">
            <img class="projLogo" src="../assets/plainvanilla.png">
          </div>

          <div class="col-lg-8 col-md-7 col-sm-9">
            <a class="content1 link" target="_blank" href="https://plainvanilla.com.sg/">Plain Vanilla Product & Sales Analysis</a>
            <p class="content2">Spreadsheet Modeling & Analytics | School Project</p>
            <p class="content2">Jan 2022 - Apr 2022</p>
            <p class="content4">Performance dashboard to analyse online sales data, forecasting of sales to optimise labour allocation, forecasting profit based on marketing strategies.</p>
          </div>

          <div class="col-md-3">
            <div class="logoContainer">
              <img class="skillLogo" src="../assets/excel.png">
            </div>
          </div>
        </div>
      </div> -->

      <project
        :projectLogo="plainVanillaLogo"
        companyLink="https://plainvanilla.com.sg/"
        projectName="Plain Vanilla Product & Sales Analysis"
        title="Spreadsheet Modeling & Analytics | School Project"
        startDate="Jan 2022"
        endDate="Apr 2022"
        description="Performance dashboard to analyse online sales data, forecasting of sales to optimise labour allocation, forecasting profit based on marketing strategies."
        :skillLogos="[excelLogo]" />


    </div>
  </main>
    
</template>

<script>
// import necessary logos
import keppelLogo from '../assets/keppel.png';
import laptopLogo from '../assets/laptop.png';
import h365Logo from '../assets/h365.png';
import lifeBelowWaterLogo from '../assets/lifebelowwater.png';
import allInOneLogo from '../assets/allinone.png';
import ecopalLogo from '../assets/ecopal.png';
import timperioLogo from '../assets/timperio.png';
import smugLogo from '../assets/smug.png';
import sentimentAnalysisLogo from '../assets/sentimentanalysis.png';
import plainVanillaLogo from '../assets/plainvanilla.png';
import mssqlLogo from '../assets/mssql.png';
import htmlLogo from '../assets/html.png';
import javascriptLogo from '../assets/javascript.png';
import cssLogo from '../assets/css.png';
import bootstrapLogo from '../assets/bootstrap.png';
import vueLogo from '../assets/vue.png';
import pythonLogo from '../assets/python.png';
import flaskLogo from '../assets/flask.png';
import mysqlLogo from '../assets/mysql.png';
import postgresqlLogo from '../assets/postgresql.png';
import rabbitmqLogo from '../assets/rabbitmq.png';
import dockerLogo from '../assets/docker.png';
import tableauLogo from '../assets/tableau.png';
import figmaLogo from '../assets/figma.png';
import twitterLogo from '../assets/twitter.png';
import redditLogo from '../assets/reddit.png';
import excelLogo from '../assets/excel.png';
import typescriptLogo from '../assets/typescript.png';
import reactLogo from '../assets/react.png';
import javaLogo from '../assets/java.png';
import springbootLogo from '../assets/springboot.png';

import project from '../components/project.vue';

export default {
  components: {
    project,
  },
  data() {
    // return the imported logos
    return {
      keppelLogo,
      laptopLogo,
      h365Logo,
      lifeBelowWaterLogo,
      allInOneLogo,
      ecopalLogo,
      timperioLogo,
      smugLogo,
      sentimentAnalysisLogo,
      plainVanillaLogo,
      mssqlLogo,
      htmlLogo,
      javascriptLogo,
      cssLogo,
      bootstrapLogo,
      vueLogo,
      pythonLogo,
      flaskLogo,
      mysqlLogo,
      postgresqlLogo,
      rabbitmqLogo,
      dockerLogo,
      tableauLogo,
      figmaLogo,
      twitterLogo,
      redditLogo,
      excelLogo,
      typescriptLogo,
      reactLogo,
      javaLogo,
      springbootLogo
    }
  }
}

</script>

<style>
  .mainbox {
    border: 1px solid rgb(93, 135, 188);
    background-color: rgb(226, 235, 244);
    color: white;
    padding: 10px;
    border-radius: 12px;
    margin-left: auto;
    margin-bottom: 10px;
    width: 60%;
    vertical-align: middle;
  }

  .box {
    border: 1px solid rgb(93, 135, 188);
    padding: 10px;
    border-radius: 12px;
    margin-left: auto;
    margin-bottom: 10px;
    width: 60%;
    vertical-align: middle;
  }

  main {
    margin-top: 150px;
  }

  .link {
    margin: 0px; 
    text-decoration: none;
  }

  p {
    margin: 0px;
  }

  .projLogo {
    width: 100%;
    max-width: 80px;
    display: block;
  }

  .skillLogo {
    display: block;
    margin: 5px;
    max-width: 40px;
  }

  .logoContainer {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

</style>