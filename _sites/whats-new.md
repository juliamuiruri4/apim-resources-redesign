---
title: What's New
index: 2
description: Azure API Management service changelog.
---

<section class="content-floating">
<h1>What's New</h1>

Visit the Azure API Management <a href="https://github.com/Azure/API-Management/blob/main/changelogs/api-management-service.md">service changelog</a> for the latest updates and new features.

<section id="announcements">
   <article>
      <div class="spec-hl"> 
        <img src="{{ 'assets/img/workspace.png' | relative_url }}" class="specs-logo">
         <h3>
            <a href="https://techcommunity.microsoft.com/blog/integrationsonazureblog/announcing-general-availability-of-workspaces-in-azure-api-management/4210796">Workspaces in API Management are now Generally Available</a>
         </h3>
     </div>
      We are excited to announce the general availability of workspaces in Azure API Management! Workspaces enable organizations to manage APIs more productively, securely, and reliably using a federated approach.<br/>
   </article>
   <article>
      <div class="spec-hl"> 
        <img src="{{ 'assets/img/genai.png' | relative_url }}" class="specs-logo">
         <h3>
            <a href="https://techcommunity.microsoft.com/blog/integrationsonazureblog/expanding-genai-gateway-capabilities-in-azure-api-management/4214245">Expanding GenAI Capabilities in APIM for a wide range of LLMs</a>
         </h3>
     </div>
      Announcing new policies to support a wider range of large language models through Azure AI Model Inference API.<br/>
   </article>
   <article>
      <div class="spec-hl"> 
        <img src="{{ 'assets/img/wordpress.png' | relative_url }}" class="specs-logo">
         <h3>
            <a href="https://techcommunity.microsoft.com/blog/integrationsonazureblog/expanding-genai-gateway-capabilities-in-azure-api-management/4214245">Public Preview of APIM Wordpress plugin for customized developer portals</a>
         </h3>
     </div>
      Azure API Management WordPress plugin enables our customers to leverage the power of WordPress to build their own unique developer portal.<br/>
   </article>
</section>
</section>

<section class="genai-capabilities">
   <div class="floating-right">
   <h2>Generative AI Capabilities in APIM</h2>
   <!-- <div id="tc-members">
         <a href="https://www.cisco.com/" target="_blank"><img src=" {{ 'assets/img/tc-cisco.png' | relative_url }}" class="tc-logo" alt="Cisco logo" title="Cisco"></a>
         <a href="https://www.emqx.com/en" target="_blank"><img src=" {{ 'assets/img/tc-emq.png' | relative_url }}" class="tc-logo" alt="EMQ logo" title="EMQ"></a>
         <a href="https://www.hivemq.com" target="_blank" ><img src=" {{ 'assets/img/tc-hivemq.png' | relative_url }}" class="tc-logo" alt="HiveMQ logo" title="HiveMQ"></a>
         <a href="https://www.ibm.com" target="_blank"><img src=" {{ 'assets/img/tc-ibm.png' | relative_url }}" class="tc-logo" alt="IBM logo" title="IBM"></a>
         <a href="https://www.microsoft.com" target="_blank"><img src=" {{ 'assets/img/tc-microsoft.png' | relative_url }}" class="tc-logo" alt="Microsoft logo" title="Microsoft"></a>
         <a href="https://www.ninefx.com" target="_blank"><img src=" {{ 'assets/img/tc-ninefx.png' | relative_url }}" class="tc-logo" alt="Ninefx Logo logo" title="Ninefx"></a>
         <a href="https://www.softwareag.com/" target="_blank"><img src=" {{ 'assets/img/tc-software-ag.png' | relative_url }}" class="tc-logo" alt="Software-AG logo" title="Software-AG"></a>
         <a href="https://www.solace.com/" target="_blank"><img src=" {{ 'assets/img/tc-solace.png' | relative_url }}" class="tc-logo" alt="Solace logo" title="Solace"></a>
         <a href="https://thingstream.io/" target="_blank"><img src=" {{ 'assets/img/tc-thingstream.png' | relative_url }}" class="tc-logo" alt="Thingstream logo" title="Thingstream"></a>
   </div> -->
      <article class="use-case">
         <div class="use-case-description">
            <p>Azure API Management has built a set of GenAI Gateway capabilities, designed specifically for GenAI use cases</p>          
         </div>
         <img src="{{ '/assets/img/genai-capabilities.gif' | relative_url }}" class="use-case-img">
      </article>
      <article class="use-case">
         <img src="{{ '/assets/img/token-limit.gif' | relative_url }}" class="use-case-img">
         <div class="use-case-description">
            <h4>Azure OpenAI Token Limit Policy</h4>
            <p>Azure OpenAI Token Limit policy allows you to manage and enforce limits per API consumer, based on the usage of Azure OpenAI tokens</p>         
            <a href="https://learn.microsoft.com/en-us/azure/api-management/llm-token-limit-policy"><button class="get-started-btn">Get Started</button></a> 
         </div>
      </article>
      <article class="use-case">
         <div class="use-case-description">
            <h4>Azure OpenAI Emit Token Metric Policy</h4>
            <p>Azure OpenAI enables you to configure token usage metrics to be sent to Azure Applications Insights, providing overview of the utilization of Azure OpenAI models across multiple applications or API consumers. </p>         
            <a href="https://learn.microsoft.com/en-us/azure/api-management/llm-emit-token-metric-policy"><button class="get-started-btn">Get Started</button></a> 
         </div>
        <img src="{{ '/assets/img/emit-token.gif' | relative_url }}" class="use-case-img">
      </article>
      <article class="use-case">
        <img src="{{ '/assets/img/load-balancing.gif' | relative_url }}" class="use-case-img">
         <div class="use-case-description">
            <h4>Load Balancer and Circuit Breaker</h4>
            <p>Load Balancer and Circuit Breaker features allow you to spread the load across multiple Azure OpenAI endpoints.</p>         
            <a href="https://learn.microsoft.com/en-us/azure/api-management/backends?tabs=bicep"><button class="get-started-btn">Get Started</button></a> 
         </div>
      </article>
      <article class="use-case">
         <div class="use-case-description">
            <h4>Azure OpenAI Semantic Caching policy</h4>
            <p>Azure OpenAI Semantic Caching policy empowers you to optimize token usage by leveraging semantic caching, which stores completions for prompts with similar meaning. </p>         
            <a href="https://learn.microsoft.com/en-us/azure/api-management/azure-openai-semantic-cache-store-policy"><button class="get-started-btn">Get Started</button></a> 
         </div>
        <img src="{{ '/assets/img/semantic-caching.gif' | relative_url }}" class="use-case-img">
      </article>
   </div>
</section>