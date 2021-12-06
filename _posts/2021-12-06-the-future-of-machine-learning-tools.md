---
toc: false
layout: post
description: My take on trends in machine learning tooling and predictions for the future. 
categories: [machine learning, tools]
title: The Future of Machine Learning Tools
---

There&#39;s an important choice all of us need to make regularly, and that is where to spend our time and energy. Especially in a field as broad as machine learning, it might be reasonable to focus on an area that has a future potential. I&#39;ve prepared a few predictions for myself and would like to share them broadly. I hope some of you will challenge my thinking and improve it!

I&#39;ve been observing machine learning from two perspectives. One is working in a traditional enterprise and looking for ways we can transform business processes to benefit from machine learning capabilities. The second is being a data science practitioner: collecting and cleaning data, training models and tinkering with their architectures. In both of these roles, I&#39;ve made some observations that I will share and then try to spot the trends and extrapolate them.

## Trends

### Trend 1 – Improving the UX for data scientists

The tooling for data scientists and machine learning engineers is a hot industry right now, and everyone is trying to win with better UX. You can download a powerful pretrained model with one line of code using HuggingFace Transformers, you can log your experiment metrics with one line of code using Weights &amp; Biases, you can easily deploy with your cloud provider. Rather than spending your time experimenting with different features or model architectures, you can use AutoML tools like H2O. This means less time spent on writing boilerplate code, and more time spent on looking at data.

### Trend 2 – More powerful pretrained models and architectures being open sourced

Big research labs keep pushing the boundaries on model sizes, training protocols and architectures. These pretrained models are often open sourced and made available &quot;for the masses&quot;. We can use them to achieve better results or solve problems with less training data. Even though the compute budgets for inference may be limiting initially, model distillation, better inference methods and cheaper compute are likely to remove that barrier soon.

### Trend 3 – Increasing role of business subject matter expert

With increasing automation of machine learning workflows, the key to developing successful models shifts to having good understanding of a business problem and sufficient amount of well labeled data. This is the domain of business subject matter experts – as long as they get proper level of training to understand concepts like train/test split and performance metrics, they should be able to build well performing models without much help of a data scientist. A big number of startups try to support this trend by offering tools that hide the training cycle behind a well-designed interface, pretrain models on domain-specific datasets and support the whole lifecycle from data labeling to deployment.

### Trend 4 – Increasing regulation

Many countries either have started regulating machine learning or are advancing projects to implement regulations in the near future. We may need to frequently update datasets if they contain personal information. We will need to record our experiments and take care of reproducibility. We will also need to have good insights on potential biases encoded in our models.

## Parallels

One way to make predictions is seeking parallels in history or in adjacent fields. Let&#39;s consider some of these parallels and try to compare them with machine learning.

### Comparison 1: Web Programming

I still remember building a simple HTML website myself many years ago… It was a nice feeling, but the website was kind of ugly. Right now, we can easily setup a nice static website with an attractive template and host it for free on Github Pages. But the bulk of work moved to complex web applications, with constantly changing frameworks, and a suite of DevOps tools to support deployment. Even though the field is quite mature now and there are some strong platforms like Wordpress, there is still plenty of work for web developers as businesses want to differentiate.

### Comparison 2: Enterprise Automation

On the enterprise side, many companies went through a very long journey of moving from manual processes or custom automations, through adoption of ERP systems that provided reference models of business processes and offered a configurable solution to automate a bunch of business processes in an integrated way, to dedicated solutions that address specific opportunities left after implementing ERP. These dedicated solutions are either coming from external suppliers that specialized in a niche business problem, or are developed internally, often on top of automation platforms such as Pega, Salesforce or UiPath.

### Comparison 3: Mobile App Stores

Opening up app stores on mobile platforms like iOS or Android resulted in a large number of independent developers making business developing and selling games and apps. Over time, the field has become much more difficult for small and independent players, as big studios operate with much bigger budgets for product and marketing.

## Predictions

What do these trends and parallels tell us about potential future developments? I will try to make some predictions.

### Prediction 1: Datasets

The competitive advantage in machine learning is increasingly moving to data. Some companies have proprietary datasets and will try to use it for their advantage. There are some problems though where independent players may be able to build useful datasets and sell them for profit. I expect a large number of small players benefitting from this initially, but ultimately the market will consolidate in a few big players. Somebody will offer a Dataset Appstore, make it easy to license and sell datasets, and make good profit on commissions. The datasets will be carefully designed, for example validation split will offer standard ways to evaluate models with respect to potential biases and adversarial scenarios.

### Prediction 2: Split into model manufacturers and users

This is already happening – big research labs like Google, Meta or Amazon are pushing out new model architectures and pretrained models. We will likely see this trend continue, and I expect more differentiation in the approaches, methods and tooling for building new model architectures and pretrained models vs. using them to solve a downstream business problem.

### Prediction 3: Standard solutions and differentiation

I initially thought we won&#39;t need that many data scientists outside of the big research labs, and the work will move to business subject matter experts. But thinking how web programming evolved, we didn&#39;t all move to WIX or Weebly. Where possible, standard solutions will emerge and become commoditized (we don&#39;t need all to develop another model to read invoices). Still, companies will want to compete and differentiate and will likely keep using (more) data scientists for this purpose. Data scientists will collaborate very closely with SMEs and are likely to find new ways or approaches to combine various data sources, frame problems, experiment to have a better performing model vs. competition. We will also have more models integrated into products and with other processes in enterprises.

### Prediction 4: Machine Learning Platforms &amp; Tools

What will machine learning tooling landscape look like in several years?

1. **General purpose platforms**. Most companies will build on top of a general purpose platform, supporting the E2E lifecycle from data labelling through model training to deployment and monitoring. Big cloud vendors have an advantage here as they have the engineering bench to build and integrate all components and combine that with compute.
2. **Specialized tools**. We will have competitors innovating on the edges of general purpose platforms and trying to grab a chunk of the space by offering a better, differentiated product. These tools will need to offer superior value and user experience, and at the same time integrate well with the underlying platforms. Given that looking at data is going to be a big trend for data scientists in my opinion, I expect many of these specialized tools to focus on data.
3. **Research tools**. I think we&#39;re going to see a category of tools to support the research work happening in the big labs. These will require a strong engineering edge to meet special needs of bigger models and datasets and do it better than the big labs themselves.
4. **Dedicated apps for specific commodity tasks**. A lot of models will become a commodity. Whenever multiple companies try to solve a specific problem with data, there will be a supplier attempting to provide a general solution to that problem. It will collect data, build and test models, and offer a packaged solution solving problems such as interpreting invoices, understanding emails, analyzing product images etc.

What do you think about these predictions? It&#39;s very likely I&#39;m partially or completely wrong, and would love to hear different perspectives.
