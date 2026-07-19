---
---

<h1> Rental Legislation in Victoria </h1>

<p>Much of Australia is facing a housing crisis. With more renters than before, the services that provide assistance in understanding the legislation and your rights within a rental situation are facing quite a bit of pressure. <a href="https://tenantsvic.org.au/">Tenants Victoria</a>, who operate a well known service within my locality, noted in their 2024-25 annual report that despite expansion of their services, "...only 15-20% of all calls by renters are able to get through to us for help." (Tenants Victoria, 2025). That's a problem.</p>

<p><a href="https://www.consumer.vic.gov.au/housing/renting">Consumer Affairs Victoria</a> provides a really useful set of pages discussing renters rights, but they can miss the opportunity to provide references back to the legislation itself. VCAT provides an excellent set of referrals to legal assistance on their <a href="https://www.vcat.vic.gov.au/what-vcat-does/legal-help-and-advice-services">'Legal help and advice services'</a> page.</p>

<p>As someone who likes playing with open language models, I want to know how useful they might be in navigating the legislation to help a user understand what parts of the legislation might be relevant to their query, and where that information lives in the document. What problems are cropping up in this space, and are they manageable through clever design and engineering, or are they unavoidable?</p> 

<p><blockquote>I want to be very clear here: <strong>A language model, including any of the projects outlined below, IS NOT A REPLACEMENT for human provided legal services.</strong> We all know that models hallucinate and leave key information out. <strong> DO NOT rely on the below projects. </strong>These projects are to test where the problems might appear. They will be out of date a lot of the time, they will not have nuanced answers, they will not be defendable in a court. Please go get yourself a lawyer - there are plenty of options on that VCAT page above.</blockquote></p>

<p>This project will use retrieval-augmented generation, database tagging, five open models (one to write, four to assess the answer), an evaluation process, and a final decision making process. Phew!</p>

<h2> Project Timeline 2026</h2>
<p><ul>
<li>Database build: complete!</li>
<li>Model selection: complete!</li>
<li>Initial code build: complete!</li>
<li>Initial run and test: complete!</li>
<li>Code adjustments for better product: July 2026</li>
<li>Next data collection: August 2026</li>
<li>Analysis: August 2026</li>
<li>Write up: September-October 2026</li>
</ul></p>

<h2> Models used in this project </h2>
<p>This project uses a mix of models at different points in the system. Gpt-OSS is the only Mixture of Experts model. Both Mistral Small and Granite are non-reasoning models. Qwen 3.6 has reasoning turned <strong>off</strong> within this project; Gpt-Oss has thinking as the default <strong>medium</strong>. Gemma's reasoning is turned <strong>on</strong>.</p>
<ul>
<li>Gemma 4 in 26B</li>
<li>Gpt-OSS in 20B</li>
<li>Granite 4.1 in 8B</li>
<li>Mistral Small 3.2 in 24B</li>
<li>Qwen 3.6 in 27B</li>
</ul>

<h2> Outputs </h2>
<p>Sorry, it's still a bit too early, there are no direct outputs yet. </p>


<h2> References </h2>
Tenants Victoria (2025) "Annual Report 2024-25", <a href="https://tenantsvic.org.au/wp-content/uploads/2025/10/Tenants-Victoria-Annual-Report-2024-2025.pdf">PDF for the 2024-25 Annual Report</a>, page 13

