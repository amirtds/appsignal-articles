# Introduction

- [ ] Discuss the concept of performance in the context of web applications
- [ ] Emphasizing its significance and general impact on user experience and operational efficiency.

## Django Performance Monitoring Essentials

- [ ] Explore key metrics for gauging the performance of Django applications
- [ ] Explain metrics related performance monitoring to handle concurrent users, database operations efficiency, and the management of long-running tasks.

## What we are going to build

- [ ] Talk about AppSignal and how we are going to integrate it with a Django application to measure performance of our application

## Project Setup

- [ ] Install libraries and requiernments
- [ ] Prepare the project structure

### Monitor Concurrent users

- [ ] Integrate AppSignal to monitor concurrent users
- [ ] Experiment the monitoring by using Locust

### database operations

- [ ] Integrate AppSignal to monitor database operations. 
- [ ] Experiment by using Djnaog ORM to create objects and monitor it's performance specially for large number of objects (CRUD operation)

### long running tasks

- [ ] Setup Celery for long running task
- [ ] Experiment by showing how AppSignal can monitor the performance. Would be great to show before/after celery implementation to show performance improvment.

## Using AppSignal with an existing Django APP

In this section we are going to see how we can integrate AppSignal with [Open edX](https://openedx.org/) which is an Open source Learning management system based on Python and Django, as a case study. 

- [ ] Integrate AppSignal with Open edX to monitor key performance metrics
- [ ] Experiment on how AppSignal can improve students experience by using performance monitoring and optimization.

## Conclusion

- [ ] Review briefly what we talked about
- [ ] Leave some questions for readers to investigate
- [ ] CTA so they can use AppSignal in their Django app