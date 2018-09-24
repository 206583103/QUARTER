# Quarter update
CHANGE INITIATION


Client submits change request to IGATE team using Project Change Request from details contain:


--Reason(s) for change 
--Detailed change description
--Timeframe within which the changes is described



CHANGE ANALYSIS


Upon receit of PCR form,IGATE will analyze and assess the impact that the change will have on

--Delivery schedule
--Engagement Objectives
--Engagement Costs 


060950d24bc74bab12b8a4476e50b489b1b2a97a 


githubClient.setCredentials(USER, TOKEN);



spring:
  profiles: "dev"

  datasource:
    driverClassName: 'oracle.jdbc.driver.OracleDriver'
    username: onair
    password: onair
    url: jdbc:oracle:thin:@//aoadbss00002c0.tfayd.com:15192/D124

git:
  userName: kodadaiah
  token: Git@2018
  repository: QUARTER
  branch: master
  commitMsg: Updated successfully
  field: "liabDateStr"
  resturl: http://localhost:8080/client

cp:
  Name: cp
  fileName: CP/test.json

dmt:
  Name: dmt
  fileName: DMT/test.json
   
mail:
  utility:
    url: https://mailing-utility.devaoa.inbcu.com/mail
 
notification:
  email:
    recipient: Mohammed.AmmarM@nbcuni.com
    sender: kodadaiah.d-p@capgemini.com
    message: Client Performance liability has been updteed to next quarter!
    subject:  CP liabliaty updated

jpa:
  database-platform: 'org.hibernate.dialect.Oracle10gDialect'
  hibernate:
   ddl-auto: none
  show-sql: true


security:
  basic:
    enabled: false
management:
  security:
    enabled: false
