---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<style>
  .bilingual-container {
    display: flex;
    flex-direction: row;
    gap: 2em;
    justify-content: space-between;
    align-items: flex-start;
    flex-wrap: wrap;
  }

  .bilingual-column {
    flex: 1;
    min-width: 300px;
    text-align: justify;
    line-height: 1.4; /* better readability with smaller font */
  }

  .arabic-column {
    direction: rtl;
  }

  .english-column {
    direction: ltr;
  }

  /* Stack columns on small screens (Arabic on top) */
  @media (max-width: 768px) {
    .bilingual-container {
      flex-direction: column-reverse;
    }
  }
</style>

<div class="bilingual-container">
  <!-- English Column (Left) -->
  <div class="bilingual-column english-column">
    <h2>Hello!</h2>
    <p>
      I work as an AI research engineer at the <a href="https://www.huawei.com/tr/corporate-information/research-development" target="_blank" rel="noopener noreferrer">Huawei R&D center</a>, Istanbul, focusing on NLP and LLMs. I hold a Master's Degree in Data Science from <a href="https://www.sabanciuniv.edu/en" target="_blank" rel="noopener noreferrer">Sabanci University</a>, Istanbul, where I conducted research in computational social science (CSS) in <a href="https://varollab.com/" target="_blank" rel="noopener noreferrer">Viral Lab</a> under the supervision of Asst. Prof. <a href="https://www.onurvarol.com/" target="_blank" rel="noopener noreferrer">Onur Varol</a>.
    </p>
    <p>
      I am interested in NLP research, especially the interpretability of LLMs and synthetic data generation. My current work covers the following aspects:
    </p>
    <ul>
      <li><strong>Finetuning LLMs</strong> on general instructions or specific tasks.</li>
      <li><strong>Designing and implementing agents</strong> including RAG, tool calling agents, content moderaton, NL2SQL, data analysis and visualization, etc.</li>
      <li><strong>Synthetic data generation</strong> for general instruction or domain-specific SFT</li>
      <li><strong>Designing data quality monitoring and filtering methods</strong> for PT and SFT data</li>
      <li><strong>Curating and chunking unstructured textual data</strong> for optimal vector database retrieval in RAG chat bots.</li>
      <li><strong>Following latest research</strong> on LLM structures, training approaches, synthetic data, etc.</li>
    </ul>
    <p>
      I am also interested in computational social science (CSS) research. During my time in <a href="https://varollab.com/">Viral Lab</a>, I worked on the following topics:
    </p>
    <ul>
      <li><strong>Developing unsupervised detection methods</strong> to detect and analyze coordinated fake-followers on social media [<a href="https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-024-00499-6" target="_blank" rel="noopener noreferrer">Paper</a>]</li>
      <li><strong>Analyzing social media data</strong> prior and during the 2023 Turkish general elections. [<a href="https://www.nature.com/articles/s41598-024-58006-w" target="_blank" rel="noopener noreferrer">Paper</a>]</li>
      <li>Analyzing the effect of a political “open discussion” program on <strong>polarization in Turkish social media.</strong></li>
      <li><strong>Clustering and analyzing social media profile images</strong> to explore signals from different political leanings.</li>
    </ul>
  </div>
  <!-- Arabic Column (Right) -->
  <div class="bilingual-column arabic-column">
    <h2>السلام عليكم!</h2>
    <p>
      أعمل مهندساً باحثاً في الذكاء الاصطناعي، تحديداً معالجة اللغة الطبيعية والنماذج اللغوية الكبيرة، في مركز البحث والتطوير لشركة هواوي  في اسطنبول (<a href="https://www.huawei.com/tr/corporate-information/research-development" target="_blank" rel="noopener noreferrer">Huawei R&D Istanbul</a>). أحمل شهادة الماجستير في تحليل البيانات من جامعة سابانجي (<a href="https://www.sabanciuniv.edu/en" target="_blank" rel="noopener noreferrer">Sabanci University</a>)، حيث عملت في مختبر <a href="https://varollab.com/" target="_blank" rel="noopener noreferrer">Viral Lab</a> تحت إشراف البروفيسور أونور فارول (<a href="https://www.onurvarol.com/" target="_blank" rel="noopener noreferrer">Onur Varol</a>) في مجال العلوم الاجتماعية الحاسوبية.
    </p>
    <p>
      أنا مهتم بالبحث في مجال معالجة اللغة الطبيعية، وخصوصا مجال تفسير النماذج اللغوية ومجال توليد البيانات الاصطناعية لتدريب النماذج اللغوية. عملي الحالي يشمل المجالات التالية:
    </p>
    <ul dir="rtl">
      <li><strong>تدريب النماذج اللغوية الكبيرة (LLMs)</strong> على مهام متخصصة أو تدريبها على التعليمات العامة.</li>
      <li><strong>تصميم وتنفيذ وكلاء من النماذج اللغوية الكبيرة</strong> مثل RAG، استدعاء الأدوات الخارجية، ضبط المحتوى المخالف، التحويل من اللغة الطبيعية إلى SQL، تحليل البيانات وإنشاء الرسوم البيانية وغيرها.</li>
      <li><strong> إنتاج بيانات نصية اصطناعية</strong> بجودة عالية تصلح للضبط الدقيق (SFT).</li>
      <li><strong>تصميم آليات لمراقبة جودة بيانات</strong> التدريب الأولي (PT) والضبط الدقيق (SFT).</li>
      <li><strong>تنظيم وتجزئة البيانات النصية غير المهيكلة</strong> لتحقيق أفضل أداء في الاسترجاع من قواعد البيانات ضمن أنظمة RAG.</li>
      <li><strong>متابعة آخر الأبحاث</strong> عن بنية النماذج اللغوية وأساليب تدريبها.</li>
    </ul>
    <p>
 أهتم أيضا بالأبحاث في مجال العلوم الاجتماعية الحاسوبية التي تحلل الظواهر الاجتماعية والسياسية على شبكات التواصل الاجتماعي. خلال بحثي في مختبر <a href="https://varollab.com/" target="_blank" rel="noopener noreferrer">Viral Lab</a>، عملت على المواضيع التالية:
    </p>
    <ul dir="rtl">
      <li><strong>تطوير آليات لضبط الحسابات الوهمية المنسقة</strong> على وسائل التواصل الاجتماعي باستخدام التعلم الآلي غير الخاضع للإشراف. [<a href="https://epjdatascience.springeropen.com/articles/10.1140/epjds/s13688-024-00499-6" target="_blank" rel="noopener noreferrer">الورقة العلمية</a>]</li>
      <li><strong>تحليل بيانات وسائل التواصل الاجتماعي</strong> قبل وخلال الانتخابات العامة في تركيا عام 2023. [<a href="https://www.nature.com/articles/s41598-024-58006-w" target="_blank" rel="noopener noreferrer">الورقة العلمية</a>]</li>
      <li>تحليل تأثير أحد برامج الحوار السياسي في تركيا على <strong>الاستقطاب في وسائل التواصل الاجتماعي</strong>.</li>
      <li><strong>تجميع وتحليل صور حسابات التواصل الاجتماعي</strong> ومعاينة ارتباطها بالتوجهات السياسية.</li>
    </ul>
  </div>
</div>