# **Resume**

## **Basic Information**

※ Last Update: 2022/08/24
|key|value|
|---|-----|
|**Name**|Kota Kawaguchi (川口輝太)|
|**Qiita**|[Qiita](https://qiita.com/kotaaaa)|
|**Twitter**|[@kotaaaa1110](https://twitter.com/kotaaaa1110)|
|**Github**|[@kotaaaa](https://github.com/kotaaaa)|
|**Research publication**|[Link](https://kk1110.com/rhp)|
|**Email**|kota.k.1132.pda@gmail.com|

## **Objective**

As a web application engineer, I am mainly involved in the back-end development of consumer electronics EC services, but also in the front-end and infrastructure areas. I am also well versed in operational tasks such as load testing in preparation for a sale.
In graduate school, I was engaged in research on data mining using natural language processing. I was selected as a JASSO scholarship recipient for exemption from repayment for my achievements during my studies, including external presentations at peer-reviewed international conferences.
Currently, I would like to get an opportunity to work as a backend engineer to work on new product development.

## **Summary**

- Software Developer with 2.5 year's experience in E-Commerce industry.
- 1 years of research internship in Data mining at Japanese Largest portal site company(Yahoo! Japan)
- Research achievements in natural language processing and web mining through 3 years

## **Strengths**

- Ability to take ownership and drive the project as a team.
- Ability to communicate smoothly with stakeholders inside and outside the team, regardless of nationality or language, and to work towards goals
- Specialized skills in data analysis and natural language processing / Analytical skills for understanding user behavior

## **Skills**

### Programming language

- **Python** (3.5y): Developed DAG with Airflow, and Used for research in natural language processing
- **Java** (2y): Used in the backend of a Home appliances EC site and in the backend of an in-house tool
- **Javascript** (2y): Used in front-end of a Home appliances EC site
- **Typescript** (3m): Used in the front-end of internal system
- **Perl** (6m): Used for text processing during research in natural language processing and web mining.
- **Shell** (3m): Write Cron process to update Nginx setting.

### Framework

- **Apache Airflow** (6m): Used as workflow management system managed. Developed 5 dags to trasfer data from external API to internal DB.
- **Spring Boot** (2y): Used in the backend of a Home appliances EC site and in the backend of an in-house tool
- **Nuxt.js,Vue.js** (2y): Frontend of Home appliances EC site
- **Angular** (3m): Used in the backend of an internal tool
- **Flask** (1m): Used for personal Linebot app creation
- **Google App Script** (3m): Transfer order data with external API
- **scikit-learn** (2y): Used as a machine learning library during research on natural language processing
- **Keras** (1y): Used as a deep learning library in research on natural language processing

### Middleware/DB/Cloud etc.

- **GCP** (6m): Developed Cloud Composer, and used BigQuery, Cloud Build, Cloud VPN, GCS, Looker, IAM management
- **Kubernetes** (2.5y): Each web application and API are operated on kubernetes.
- **Nginx** (1y): Change web server settings, etc.
- **Terraform** (2.5y): Set up GCP components with terraform.
- **Chef** (1y): Manage server settings of Nginx, etc.
- **Oracle** (2y): Used as internal DB table.

## **Work Experience**

### 2022/02 - Current : Enigmo Inc. Freelance

Job Title: Data Integration Engineer

Development and operation of the new boutique's data transfer system.

- Developed workflow to transfer item and order data with boutique's API with Apache Airflow.
- Created BI dashboard to check data transfer status with BigQuery and Looker
- Set up GCP components with Terraform.
- Upgraded Airflow and Cloud Composer Version up to 2.x from 1.x
- Installed CI/CD pipeline with Cloud Build
- GCP Project migration to build scalable system
  Tech: Airflow(Cloud Composer), GCP, Terraform, BigQuery, Looker

Tech: Airflow(Cloud Composer), GCP, Terraform, BigQuery, Looker

### 2020/04 - 2022/02 : **Rakuten Group, Inc**

Job Title: Application Engineer
As a Web Application Engineer, I am engaged in the maintenance and operation of a consumer electronics e-commerce site, as well as development projects associated with the development of the service.

#### **Development Project**

##### New Web Application development of the Internal API management system(2020/05 - 2020/06)

- Development environment construction(Docker)
- New API design / Development (Thymeleaf, Springboot)
- Implementation and unit testing (Junit)

##### Modification of the front-end part of the internal system(2020/07 - 2020/09)

- Screen Design
- Implementation and unit testing (Angular9)
- Integration Test / Production release work

##### Modification of the backend of the cash register screen and payment processing part(2020/10 - 2020/11)

- Development (API), fixed model parameter and unit testing (Springboot)
- Internal testing, external integration testing
- Phases: development and unit testing, internal testing, external coupling testing (joint testing with other companies), production release

##### Development of new abstract Batch class and csv file import batch (2020/12 - 2020/03)

- Impact survey, basic design, detail design
- Development Abstract class for Batch development and Batch development (Spring batch, Template method pattern)
- Phases: design, development and unit testing, internal testing, external coupling testing (joint testing with other companies), production release

##### Modification of product data trasfer batch (2021/04 - 2021/06)

- Modification of the logic of the product data collaboration file import batch
- Phases: design, development and unit testing, internal testing, external coupling testing (joint testing with other companies), production release
- Communicated with Biccamera team members to achieve common goal.

##### Addition of double price display logic in the product detail page (2021/07 - 2021/08)

- Modification of the product detail page, backend development of the internal API call part
- Phases: Design, development and unit testing, internal testing, external coupling testing (joint testing with other companies), production release

##### Creation of new web application and fix web Nginx server's parameters for timesale events (2021/07 - 2021/08)

- To achieve system's sustainability even in the hign load at timesale, created new application for load balancing.
  - Implement Nginx reload Shell / Prepare Jenkins pipeline for Production deploy
  - Parameter settings of Chef
  - NFS setting
  - New Web application Design, implementation to handle request to sale item.(k8s, Nuxt.js)

#### **Operation Task(Annual)**

- Preparation and execution of load tests.
  - Conducted load tests for the Rakuten Super Sale, the largest shopping event held every quarter.
  - Monitored the operation status by applying high QPS load.
- Periodic maintenance work
  - Paused and restarted batches, shifted production servers to maintenance mode, etc.
- EOL support for internal APIs, upgrade work
- Improvement and deployment of existing bugs.
- Did operation of NFS settings, ACL serttings and FTP file transfer setting.
- Production trouble shooting

#### Others

- In-house department hackathon second place: (2nd/9th)
  - Tech Stack: Vue.js
  - Title: Improve UI/UX on RFashion Search Page

## **Internship**

### 2018/07 - 2019/06 : Z Holdings Corporation

#### Department: **Yahoo! JAPAN R&D**

- Analysis of user behavior of news site viewers using user's real data
  - Research Achevement: https://www.jstage.jst.go.jp/article/pjsai/JSAI2019/0/JSAI2019_3Rin236/_article/-char/ja
- User attribute estimation task using in-house Twitter data
- Technology: python, hql (hive)

## **Education**

- University of Tsukuba (Master of Engineering) March, 2020
- University of Tsukuba (Bachelor of Engineering) March, 2018

## Natural Language

- Japanese
  - Native
- English
  - Business English
  - TOEIC: 885 (Oct 2017)
  - TOEFL iBT: 71 (May 2017)
  - IELTS: 5.5 (Jun 2015)

## Qualifications

- [Google Cloud Associate Cloud Engineer](https://www.credential.net/f0e91b5b-37a6-4257-b6cb-d983a8458e65?key=4bdeaa38e98b672109444214a4665b1a3d32836eceaefe2c1eb0969d8129a188) 2022/07
- Fundamental Information Technology Engineer Examination（基本情報技術者試験）2021/03
- Applied Information Technology Engineer Examination（応用情報技術者試験）2021/12

## Research Publication

- Summarized at my Research Home Page
  - https://kk1110.com/rhp

## Other Activity

- Atcoder(Green)
  - [Link](https://atcoder.jp/users/kotakota1110)
- Hackday in Department. Second prize: (2nd Prize/9 teams)
  - Tech Stack: Vue.js (SPA)
  - Title: Improve UI/UX on RFashion Search Page

### Presentation material (in-house)

- [Vue.js and Angular Comparison](https://docs.google.com/presentation/d/1h_P7dhnW3S0hDDh1SePlVg5xgqcNsKFr04HTVTySlzo/edit?usp=sharing)
- [Template Design with Java](https://docs.google.com/presentation/d/15R4Mw0pLo-towAo4pgqAzWp5BFoDNc7lPfxiy-tmD6c/edit?usp=sharing)
- [Nginx Basic](https://docs.google.com/presentation/d/1-I-v7pCzbTYCO33C_oP2Vug88iforBZAXDYVxoqaxO8/edit?usp=sharing)

### Awards / Scholarships

- [Repayment Exemption for Students with Excellent Grades -FY2020-, Japan Student Services Organization (JASSO) Type I (interest-free) scholarship (Half price Exemption of Scholarships](https://www.jasso.go.jp/shogakukin/taiyochu/gyosekimenjyo/index.html)
  ![image](https://user-images.githubusercontent.com/25422441/103165140-4a401380-4857-11eb-907d-457b28af81c6.png)

### Blogs

- [Qiita](https://qiita.com/kotaaaa)
