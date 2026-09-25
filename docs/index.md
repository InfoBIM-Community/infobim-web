<div class="ib-site">
  <nav class="ib-nav">
    <a class="ib-brand" href="#top" aria-label="InfoBIM">Info<span>BIM</span></a>
    <div class="ib-nav-links">
      <a href="#concept" data-i18n="navConcept">Conceito</a>
      <a href="#architecture" data-i18n="navArchitecture">Arquitetura</a>
      <a href="#applications" data-i18n="navApplications">Aplicações</a>
      <a href="#research" data-i18n="navResearch">Pesquisa</a>
      <a href="#references" data-i18n="navReferences">Referências</a>
    </div>
    <div class="ib-language" aria-label="Language">
      <button type="button" data-lang="pt" class="active">PT</button>
      <button type="button" data-lang="en">EN</button>
      <button type="button" data-lang="es">ES</button>
    </div>
  </nav>

  <section class="ib-hero" id="top">
    <div class="ib-hero-copy">
      <div class="ib-kicker" data-i18n="heroKicker">OPENBIM · DATA GOVERNANCE · AI HARNESS</div>
      <h1 data-i18n="heroTitle">Governança de Dados com OpenBIM</h1>
      <p class="ib-lead" data-i18n="heroLead">Um harness para IA e ferramentas de engenharia.</p>
      <p data-i18n="heroBody">O InfoBIM é um projeto open source de pesquisa aplicada que cria uma camada explícita de contexto, relações, regras e capacidades ao redor da informação de engenharia. Em vez de pedir que uma IA reconstrua o projeto a cada interação, o ambiente já informa o que os dados representam, como se relacionam e quais operações podem agir sobre eles.</p>
      <div class="ib-actions">
        <a class="ib-button ib-primary" href="#architecture" data-i18n="heroCta1">Explorar a arquitetura</a>
        <a class="ib-button" href="https://github.com/InfoBIM-Community/infobim-core" target="_blank" rel="noopener" data-i18n="heroCta2">Ver o código</a>
      </div>
      <div class="ib-equation">Data + Context + Rules + Capabilities = <strong>Data with Brains</strong></div>
    </div>

    <div class="ib-video-shell" aria-label="Video carousel">
      <div class="ib-video-head">
        <span data-i18n="videoLabel">Vídeos e referências</span>
        <div class="ib-carousel-controls">
          <button type="button" data-carousel="prev" aria-label="Previous video">←</button>
          <button type="button" data-carousel="next" aria-label="Next video">→</button>
        </div>
      </div>
      <div class="ib-carousel" id="ib-video-carousel">
        <article class="ib-video-card">
          <iframe src="https://www.youtube-nocookie.com/embed/RqLq6ErWfk0" title="Harness Engineering — Código Fonte TV" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          <div class="ib-video-caption">
            <strong>Harness Engineering</strong>
            <span data-i18n="video1">A referência que motivou o novo enquadramento do InfoBIM.</span>
          </div>
        </article>
        <article class="ib-video-card">
          <iframe src="https://www.youtube-nocookie.com/embed/ZN7RBcjkqV4" title="F.E.L.A. — openBIM Hackathon Porto 2026" loading="lazy" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
          <div class="ib-video-caption">
            <strong>F.E.L.A. · openBIM Hackathon 2026</strong>
            <span data-i18n="video2">Engenharia determinística, ontologias e IA aplicadas a requisitos reais.</span>
          </div>
        </article>
      </div>
    </div>
  </section>

  <section class="ib-section" id="concept">
    <div class="ib-section-label" data-i18n="conceptLabel">Dados com Cérebro</div>
    <h2 data-i18n="conceptTitle">A inteligência não precisa estar toda no modelo.</h2>
    <div class="ib-two-columns">
      <p data-i18n="conceptBody1">Um modelo de linguagem pode interpretar informação, mas não conhece automaticamente o contexto específico de um empreendimento, suas relações documentais, regras técnicas, estados ou processos. No Harness Engineering, esse problema é tratado pela infraestrutura ao redor do modelo: contexto, ferramentas, estado, regras de execução e mecanismos de verificação.</p>
      <p data-i18n="conceptBody2">O InfoBIM transporta essa ideia para a governança de dados na engenharia. Modelos IFC, PDFs, planilhas, cronogramas, imagens e outras fontes permanecem independentes, enquanto uma camada legível por máquina descreve o que representam, como se relacionam e quais operações podem ser executadas sobre elas.</p>
    </div>
    <div class="ib-callout" data-i18n="conceptCallout">A IA é uma ferramenta dentro do sistema — não a fonte da verdade.</div>
  </section>

  <section class="ib-section" id="architecture">
    <div class="ib-section-label" data-i18n="architectureLabel">Arquitetura</div>
    <h2 data-i18n="architectureTitle">Um harness para informação de engenharia.</h2>
    <div class="ib-grid ib-grid-3">
      <article class="ib-card"><span>01</span><h3 data-i18n="cardInfoTitle">Informação</h3><p data-i18n="cardInfoBody">IFC, PDF, DWG/DXF, XLSX, imagens, cronogramas e outros recursos continuam em seus formatos originais.</p></article>
      <article class="ib-card"><span>02</span><h3 data-i18n="cardContextTitle">Contexto</h3><p data-i18n="cardContextBody">Estruturas semânticas descrevem identidade, significado, proveniência e relações entre recursos.</p></article>
      <article class="ib-card"><span>03</span><h3 data-i18n="cardGuidesTitle">Guides</h3><p data-i18n="cardGuidesBody">Ontologias, requisitos, regras, estados e políticas orientam ferramentas e agentes antes da execução.</p></article>
      <article class="ib-card"><span>04</span><h3 data-i18n="cardCapabilitiesTitle">Capabilities</h3><p data-i18n="cardCapabilitiesBody">IA, scripts, validadores, conversores, visualizadores, consultas e APIs tornam-se operações descobríveis.</p></article>
      <article class="ib-card"><span>05</span><h3 data-i18n="cardSensorsTitle">Sensors</h3><p data-i18n="cardSensorsBody">SHACL, testes, regras, consultas e avaliações inferenciais verificam os resultados produzidos.</p></article>
      <article class="ib-card"><span>06</span><h3 data-i18n="cardOrchestrationTitle">Orquestração</h3><p data-i18n="cardOrchestrationBody">Capabilities, eventos e máquinas de estado definem o que pode acontecer e em qual contexto.</p></article>
    </div>
  </section>

  <section class="ib-section ib-split-section">
    <div>
      <div class="ib-section-label">Guides + Sensors</div>
      <h2 data-i18n="guidesTitle">Prevenir antes. Verificar depois.</h2>
    </div>
    <div class="ib-grid ib-grid-2">
      <article class="ib-panel"><div class="ib-panel-tag">FEED-FORWARD</div><h3>Guides</h3><p data-i18n="guidesBody">Fornecem contexto, restrições e estruturas antes da execução. No InfoBIM, podem ser ontologias, requisitos, estados, relações semânticas ou instruções associadas a uma capability.</p></article>
      <article class="ib-panel"><div class="ib-panel-tag">FEEDBACK</div><h3>Sensors</h3><p data-i18n="sensorsBody">Atuam sobre o resultado e verificam se o novo estado atende às condições definidas pelo ambiente, por mecanismos determinísticos ou inferenciais.</p></article>
    </div>
  </section>

  <section class="ib-section ib-dark-band">
    <div class="ib-section-label" data-i18n="deterministicLabel">Princípio de projeto</div>
    <h2 data-i18n="deterministicTitle">Determinístico onde é possível. Inferencial onde é necessário.</h2>
    <p data-i18n="deterministicBody">Nem todo problema de engenharia precisa de IA. Quando uma regra pode ser expressa formalmente, uma ferramenta determinística deve executá-la ou verificá-la. Quando o problema exige interpretação semântica, linguagem natural ou julgamento contextual, um modelo de IA pode participar. As duas formas de computação coexistem dentro do mesmo harness.</p>
  </section>

  <section class="ib-section">
    <div class="ib-section-label">OpenBIM</div>
    <h2 data-i18n="openbimTitle">Padrões abertos como infraestrutura de contexto.</h2>
    <div class="ib-standard-row">
      <div><strong>IFC</strong><span data-i18n="ifcText">dados BIM abertos</span></div>
      <div><strong>ISO 21597 / ICDD</strong><span data-i18n="icddText">relações entre recursos distribuídos</span></div>
      <div><strong>RDF</strong><span data-i18n="rdfText">relações legíveis por máquina</span></div>
      <div><strong>SPARQL</strong><span data-i18n="sparqlText">consulta do contexto</span></div>
      <div><strong>SHACL</strong><span data-i18n="shaclText">restrições verificáveis</span></div>
    </div>
    <p class="ib-wide-copy" data-i18n="openbimBody">O objetivo não é substituir ferramentas existentes, mas permitir que diferentes ferramentas compartilhem uma camada aberta de contexto e governança. Os arquivos continuam arquivos; as relações tornam-se computáveis.</p>
  </section>

  <section class="ib-section" id="applications">
    <div class="ib-section-label" data-i18n="applicationsLabel">Aplicações</div>
    <h2 data-i18n="applicationsTitle">Uma infraestrutura. Diferentes executores.</h2>
    <div class="ib-grid ib-grid-3 ib-apps">
      <article class="ib-card"><h3 data-i18n="app1Title">Governança documental</h3><p data-i18n="app1Body">Relacionar arquivos, modelos, requisitos e evidências preservando contexto e proveniência.</p></article>
      <article class="ib-card"><h3 data-i18n="app2Title">Verificação</h3><p data-i18n="app2Body">Combinar IFC, regras formais e mecanismos de validação reproduzíveis.</p></article>
      <article class="ib-card"><h3 data-i18n="app3Title">Automação de engenharia</h3><p data-i18n="app3Body">Descobrir e executar capabilities apropriadas ao tipo e ao estado da informação.</p></article>
      <article class="ib-card"><h3 data-i18n="app4Title">IA contextualizada</h3><p data-i18n="app4Body">Fornecer aos agentes contexto técnico estruturado sem depender apenas de prompts extensos ou RAG.</p></article>
      <article class="ib-card"><h3 data-i18n="app5Title">Rastreabilidade</h3><p data-i18n="app5Body">Registrar relações entre informação, operações executadas e resultados produzidos.</p></article>
      <article class="ib-card"><h3 data-i18n="app6Title">Integração</h3><p data-i18n="app6Body">Permitir que ferramentas tradicionais, scripts e IA operem sobre a mesma camada de informação.</p></article>
    </div>
  </section>

  <section class="ib-section" id="research">
    <div class="ib-section-label" data-i18n="researchLabel">Pesquisa aplicada</div>
    <h2 data-i18n="researchTitle">Software e experimento arquitetural.</h2>
    <div class="ib-two-columns">
      <p data-i18n="researchBody1">A pesquisa investiga como princípios de Harness Engineering podem ser transportados do domínio de agentes de software para a governança de dados no ambiente construído.</p>
      <p data-i18n="researchBody2">A hipótese é que informações de engenharia podem carregar descrições legíveis por máquina de seu contexto, relações e operações aplicáveis, permitindo colaboração entre ferramentas determinísticas, aplicações tradicionais e agentes de IA sem colocar o LLM no centro da arquitetura.</p>
    </div>
    <div class="ib-research-note" data-i18n="researchNote">InfoBIM é uma implementação open source dessa investigação, construída sobre o runtime semântico OntoBDC e alinhada a uma arquitetura local-first de malha semântica executável.</div>
  </section>

  <section class="ib-section" id="references">
    <div class="ib-section-label" data-i18n="referencesLabel">Referências conceituais</div>
    <h2 data-i18n="referencesTitle">Harness Engineering como base, engenharia como domínio.</h2>
    <div class="ib-reference-list">
      <a href="https://mitchellh.com/writing/my-ai-adoption-journey" target="_blank" rel="noopener"><strong>Mitchell Hashimoto</strong><span>My AI Adoption Journey · 2026</span><p data-i18n="ref1Body">Erros recorrentes devem se transformar em melhorias permanentes do harness por regras ou ferramentas de verificação.</p></a>
      <a href="https://martinfowler.com/articles/harness-engineering.html" target="_blank" rel="noopener"><strong>Birgitta Böckeler</strong><span>Harness Engineering for Coding Agent Users · 2026</span><p data-i18n="ref2Body">Organiza o harness em Guides e Sensors, com controles computacionais e inferenciais.</p></a>
      <a href="https://www.langchain.com/blog/the-anatomy-of-an-agent-harness" target="_blank" rel="noopener"><strong>Vivek Trivedy</strong><span>The Anatomy of an Agent Harness · 2026</span><p data-i18n="ref3Body">Define Agent = Model + Harness e deriva estado, ferramentas, execução, memória, contexto e verificação como infraestrutura ao redor do modelo.</p></a>
    </div>
  </section>

  <section class="ib-final">
    <div>
      <div class="ib-section-label">OPEN RESEARCH · REAL ENGINEERING</div>
      <h2 data-i18n="finalTitle">IA raciocina. O harness governa o contexto em que ela age.</h2>
      <p data-i18n="finalBody">InfoBIM é open source, Apache 2.0, desenvolvido no Brasil para problemas reais de interoperabilidade, governança, validação e automação na engenharia.</p>
    </div>
    <div class="ib-actions">
      <a class="ib-button ib-primary" href="https://github.com/InfoBIM-Community/infobim-core" target="_blank" rel="noopener">GitHub</a>
      <a class="ib-button" href="mailto:community@infobim.org" data-i18n="contact">Contato</a>
    </div>
  </section>
</div>
