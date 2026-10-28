<a href="https://gabriel-oliveira-portfolio-neon.vercel.app">
  <img src="./assets/hero.svg" width="100%" alt="Gabriel Oliveira, Full Stack Software Engineer. I build systems that scale: APIs and event-driven architectures on AWS that process millions of records a day, and I study Artificial Intelligence to take them further." />
</a>

<br/>

<img src="./assets/about.svg" width="100%" alt="About: code that scales. 8+ years of experience, millions of records processed every day, 200k+ records per month at peak in an integration I designed." />

I'm a **Full Stack Software Engineer** with **8+ years** building and integrating systems. At **Total Express** I work on event-driven architectures on AWS that connect operations to a huge network of partners: from marketplaces like **Amazon, Mercado Livre, Shopee, Magazine Luiza, AliExpress, TikTok and SHEIN** to banks like **Nubank, Inter and Bradesco** in card operations.

I've worked as a **tech lead**, I join technical meetings with **international clients in English**, and I'm studying **Artificial Intelligence at FIAP**, going deeper into LLMs, neural networks and Data Science.

<br/>

<img src="./assets/expertise.svg" width="100%" alt="Areas of expertise. Backend: PHP, Laravel, Python, REST APIs and microservices, testing with PHPUnit and pytest. Cloud and events: AWS Lambda, SQS, SNS, S3, API Gateway, DynamoDB, Kafka, Amazon MSK, RabbitMQ. Infra and frontend: Docker, CI/CD with Jenkins, MySQL, JavaScript, TypeScript, React. AI and data: Machine Learning, Generative AI, LLMs, RAG, Data Science." />

<br/>

<img src="./assets/experience.svg" width="100%" alt="Experience timeline: Argus (2018–2019), ZPT Digital (2019–2022), Total Express (2022–today)." />

**Full Stack Software Engineer · Total Express** · 2022 – today<br/>
<sub>2022–2024 contracted through Plus-IT Tech</sub>

- Laravel REST APIs and microservices for large-scale e-commerce integrations.
- Asynchronous architectures with **Kafka and RabbitMQ** processing **millions of records a day**.
- **AWS Lambda** + **SQS** for scalable async processing; unit and integration tests with PHPUnit, pytest and unittest.

**Tech Lead · ZPT Digital** · 2021 – 2022

- Led the development committee and sprint planning; technical direction of the team's deliveries.

**Full Stack Developer · ZPT Digital** · 2019 – 2022

- Front-end and back-end with PHP, C#, Python and JavaScript; MySQL/SQL administration and server maintenance.
- Server and database migrations, files to **AWS S3**, scheduled jobs on **EC2** and APIs connecting internal systems.

**Internships · Support & Development · ZPT Digital (2019) and Argus (2018 – 2019)**

- Development and support of the main systems, requirements analysis and customer support.

<br/>

<img src="./assets/impact.svg" width="100%" alt="Impact stories. Amazon International Integration, end-to-end owner: 200k+ records per month at peak, 17 Lambda functions, 18 SQS queues, 5 EventBridge schedules, 6 tables. CloudWatch cost reduction, active contributor: US$ 5k cut from logging costs." />

<details>
<summary><b>How the Amazon International integration works</b></summary>
<br/>

1. **Capture.** EventBridge schedules trigger Lambdas that pull manifests, commercial invoices and KYC data from Amazon's SFTP, decrypting the files. A flow control built on S3 and SNS only starts processing once every file has arrived.
2. **Processing.** Each manifest gets a unique ID, is split into configurable batches stored on S3, and goes through a chain of SQS + Lambda steps that add KYC data and the USD exchange rate before a batched submission to the international partner.
3. **Tracking & feedback.** Statuses are fetched in batches, mapped through a lookup table and sent back to Amazon as XML over SFTP. Every queue has a DLQ, and failures go to an error log table that generates the error report for Amazon.

</details>

<br/>

<img src="./assets/education.svg" width="100%" alt="Education: Artificial Intelligence at FIAP (2025–2027) and IT Technician at ETEC (2017–2018). Finalist at the FIAP + Google Cloud Hackathon 2025 with MoveLens." />

**Certifications:** Machine Learning Professional (FIAP, 2025) · Introduction to Generative AI (Google Cloud, 2025) · Gen AI Hackathon (FIAP · Google Cloud, 2025) · Oracle Certified Foundations Associate (2024) · Introduction to Python (DataCamp, 2024) · Linux Terminal (Udemy, 2024)

**Languages:** Portuguese (native) · English (professional)

<br/>

<img src="./assets/contact.svg" width="100%" alt="Let's talk? gosantos.dev@gmail.com" />

<p align="center">
  <a href="https://gabriel-oliveira-portfolio-neon.vercel.app"><img src="./assets/btn-portfolio.svg" height="44" alt="Portfolio" /></a>
  &nbsp;
  <a href="https://www.linkedin.com/in/gabriel-oliveira-b6353a16b/"><img src="./assets/btn-linkedin.svg" height="44" alt="LinkedIn" /></a>
  &nbsp;
  <a href="mailto:gosantos.dev@gmail.com"><img src="./assets/btn-email.svg" height="44" alt="Email" /></a>
</p>
