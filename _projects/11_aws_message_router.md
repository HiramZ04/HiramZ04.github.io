---
layout: page
title: AWS Message Router
description: Serverless message routing pipeline using API Gateway, SQS, Lambda, EventBridge, Step Functions, SNS, DynamoDB, and S3. Presented at an AWS meetup hosted at the Amazon San Diego office.
img: assets/img/aws3.jpg
importance: 1
category: hackathon
related_publications: false
---

A serverless workflow that takes user messages from a static frontend and routes them through a multi-stage AWS pipeline: API Gateway → SQS (with DLQ) → Lambda → EventBridge → Step Functions (Map/batching) → SNS → DynamoDB → S3. X-Ray provides end-to-end observability; CodePipeline automates deployments. Built by the **AWS Tijuana** community team to practice real cloud patterns end-to-end in preparation for the **AWS Certified Developer – Associate** exam. Currently integrating LLM processing via **Amazon Bedrock** for message classification, summarization, and transformation.

**Stack:** API Gateway, SQS, Lambda, EventBridge, Step Functions, SNS, DynamoDB, S3, X-Ray, CodePipeline, Amazon Bedrock (in progress).

---

{% include figure.liquid loading="eager" path="assets/img/aws4.jpg" title="Presenting Message Router at the AWS San Diego meetup — Amazon office" class="img-fluid rounded z-depth-1" zoomable=true %}

{% include figure.liquid loading="eager" path="assets/img/aws1.jpg" title="Message Router — full AWS architecture diagram" class="img-fluid rounded z-depth-1 mt-3" zoomable=true %}

<div class="row mt-3">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/aws3.jpg" title="Amazon San Diego office — where the meetup was hosted" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/aws2.jpg" title="AWS Tijuana team presenting to the audience" class="img-fluid rounded z-depth-1" zoomable=true %}
  </div>
</div>
