<template>
  <main>
    <!-- Experience Section -->
    <div>
      <div class="container mainbox">
        <h2 class="content1">Work Experience</h2>
        <a class="content2 link" target="_blank" href="https://www.linkedin.com/in/danelle-goh/">View my LinkedIn profile for more details</a>
      </div>

      <!-- Shopee Internship -->
      <project
        :projectLogo="shopeeLogo"
        companyLink="https://careers.shopee.sg/"
        projectName="Shopee (Regional SPX)"
        title="Product Management Intern"
        startDate="May 2025"
        endDate="Current"
        description="Oversaw the product lifecycle for features related to driver governance, service points, notifications, finance and asset management. Delivered clear and comprehensive Business Requirement Documents (BRDs) and coordinated User Acceptance Testing (UAT)."
        :skillLogos="[figmaLogo, prestoLogo, atlassianLogo]" />

      <!-- Keppel Internship -->
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
        projectName="Healthy 365 for Youth"
        title="Capstone Project"
        startDate="Aug 2024"
        endDate="Nov 2024"
        description="Collaborated with the Health Promotion Board (HPB), to create an improved version of H365 targeted at youth aged 13 to 17 years old, offering a gamified experience with non-monetary rewards. Taking on the role as Scrum Master, I led my team in sprints, monitoring our progress and ensuring project completion."
        :skillLogos="[pythonLogo, flaskLogo, postgresqlLogo, javascriptLogo, vueLogo]" />

      <!-- IS442 Timperio CRM -->
      <project
        :projectLogo="timperioLogo"
        companyLink="https://github.com/onebignick/is442-project"
        projectName="Timperio Customer Relationship Management (CRM) System"
        title="Object Oriented Programming | School Project"
        startDate="Aug 2024"
        endDate="Nov 2024"
        description="The web application enables efficient visualisation of customer purchase histories and personalised marketing efforts. It also aims to enhance customer engagement, improve sales performance, and streamline the management of customer data."
        :skillLogos="[javaLogo, springbootLogo, postgresqlLogo, typescriptLogo, reactLogo]" /> 
      
      <!-- To Do List Mobile App -->
      <project
        :projectLogo="laptopLogo"
        companyLink="https://github.com/danellegoh/to-do-frontend"
        projectName="To Do List Mobile Application"
        title="Personal Project"
        startDate="Nov 2024"
        endDate="Nov 2024"
        description="Experimental project to build a To Do List, with Android as the target OS, using React Native powered by Laravel backend."
        :skillLogos="[phpLogo, laravelLogo, postgresqlLogo, typescriptLogo, reactLogo]" /> 

      <!-- IS216 Life Below Water -->
      <project
        :projectLogo="lifeBelowWaterLogo"
        companyLink="https://github.com/L1uM4rt1n/WAD2_Project"
        projectName="Life Below Water"
        title="Web Application Development | School Project"
        startDate="Aug 2023"
        endDate="Nov 2023"
        description="A web application aimed at increasing awareness and promoting action for marine conservation. It includes an interactive map, latest news, donation and volunteer pages, as well as a fun personality quiz."
        :skillLogos="[htmlLogo, javascriptLogo, cssLogo, bootstrapLogo, vueLogo]" />

      <!-- IS212 All in One -->
      <project
        :projectLogo="allInOneLogo"
        companyLink="https://github.com/junyang99/Skill_Based_portal"
        projectName="All in One - Skill-Based Portal"
        title="Software Project Management | School Project"
        startDate="Aug 2023"
        endDate="Nov 2023"
        description="Agile-managed project using scrum methodology. The application improves job application process within the organisation – for applicants, managers and HR."
        :skillLogos="[pythonLogo, flaskLogo, mysqlLogo, javascriptLogo, vueLogo]" />

      <!-- IS213 EcoPal -->
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
      <project
        :projectLogo="smugLogo"
        companyLink="https://www.figma.com/proto/33SdEPZMtDAv62nd9WFTMv/SMUG-Prototype?page-id=14%3A3971&node-id=225-4622&viewport=371%2C494%2C0.08&t=gpW2EsXm4ppxzftT-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=225%3A4622&show-proto-sidebar=1"
        projectName="SMUG - eLearn Mobile Companion"
        title="Interaction Design & Prototyping | School Project"
        startDate="Aug 2022"
        endDate="Nov 2022"
        description="Prototype of a mobile application to notify users of upcoming academic deadlines and keep track of relevant course materials. Includes gamification aimed at improving effectiveness of study sessions."
        :skillLogos="[figmaLogo]" />

      <!-- SMT203 Marijuana -->
      <project
        :projectLogo="sentimentAnalysisLogo"
        projectName="Sentiment Analysis of Legalising Recreational Marijuana in America"
        title="Computational Social Science | School Project"
        startDate="Aug 2022"
        endDate="Nov 2022"
        description="Analysed online sentiments from Twitter and Reddit using relevant APIs, breaking down into general and state-specific analysis. Conducted VADER, text, log-odds, and empath analysis."
        :skillLogos="[pythonLogo, twitterLogo, redditLogo]" />

      <!-- COR1305 PV -->
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
import shopeeLogo from '../assets/shopee.png';
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
import laravelLogo from '../assets/laravel.png';
import phpLogo from '../assets/php.png';
import prestoLogo from '../assets/presto.png';
import atlassianLogo from '../assets/atlassian.png';

import project from '../components/project.vue';

export default {
  components: {
    project,
  },
  data() {
    // return the imported logos
    return {
      shopeeLogo,
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
      springbootLogo,
      laravelLogo,
      phpLogo,
      prestoLogo,
      atlassianLogo
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