// Copy protection
document.addEventListener('contextmenu', e => e.preventDefault());
document.addEventListener('keydown', e => {
  if ((e.ctrlKey || e.metaKey) && ['c','a','u','s','p'].includes(e.key.toLowerCase())) e.preventDefault();
  if (e.key === 'F12' || (e.ctrlKey && e.shiftKey && ['i','j','c'].includes(e.key.toLowerCase()))) e.preventDefault();
});

// Animated number counter
function animateCounter(el, target, suffix = '') {
  const duration = 1800;
  const start = performance.now();
  const isFloat = target % 1 !== 0;
  const update = (now) => {
    const elapsed = now - start;
    const progress = Math.min(elapsed / duration, 1);
    const eased = 1 - Math.pow(1 - progress, 3);
    const current = Math.floor(eased * target);
    el.textContent = current + suffix;
    if (progress < 1) requestAnimationFrame(update);
    else el.textContent = target + suffix;
  };
  requestAnimationFrame(update);
}

const statObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting && !entry.target.dataset.counted) {
      entry.target.dataset.counted = '1';
      const el = entry.target.querySelector('.stat-num');
      if (!el) return;
      const text = el.textContent.trim();
      const match = text.match(/^(\d+)(\+|%)?$/);
      if (match) {
        const num = parseInt(match[1]);
        const suf = match[2] || '';
        animateCounter(el, num, suf);
      }
    }
  });
}, { threshold: 0.3 });

document.querySelectorAll('.stat-card').forEach(el => statObserver.observe(el));

const translations = {
  pt: {
    lang_label: "Idioma:",
    nav_about: "Sobre",
    nav_differentials: "Diferenciais",
    nav_services: "Serviços",
    nav_clients: "Clientes",
    nav_contact: "Contato",
    hero_eyebrow: "Petróleo & Gás · Tecnologia & Inovação",
    hero_sub: "Consultoria Especializada para a Indústria de Petróleo e Gás",
    hero_cta1: "Nossos Serviços",
    hero_cta2: "Fale Conosco",
    scroll_hint: "scroll",
    about_tag: "Quem Somos",
    about_title: "Nossa Missão",
    about_desc: "Criar soluções inovadoras que resolvam desafios complexos, melhorando a experiência dos nossos clientes e gerando valor na indústria de petróleo e gás.",
    value1_title: "Criatividade & Pensamento Disruptivo",
    value1_desc: "Estimulamos soluções não convencionais e a coragem para romper com o status quo.",
    value2_title: "Excelência",
    value2_desc: "Comprometemo-nos a entregar soluções de alta qualidade com dedicação constante.",
    value3_title: "Agilidade & Adaptabilidade",
    value3_desc: "Aprendemos rapidamente e respondemos com eficiência a um ambiente em constante mudança.",
    stat1: "Anos de Experiência",
    stat2: "Clientes Ativos",
    stat3: "Áreas de Serviço",
    stat4: "Comprometimento",
    diff_tag: "Por que a EZO",
    diff_title: "Nossos Diferenciais",
    diff_sub: "A única consultoria que integra Engenharia, Geologia, Trading e Comex sob um mesmo teto.",
    diff1_title: "35+ Anos de Mercado",
    diff1_desc: "Décadas de experiência prática na indústria brasileira e internacional de óleo e gás.",
    diff2_title: "Equipe Multidisciplinar",
    diff2_desc: "Engenheiros, geólogos, especialistas em comércio exterior e desenvolvimento de negócios em uma só parceria.",
    diff3_title: "Atuação Global",
    diff3_desc: "Rede de agentes e parceiros estratégicos em mercados internacionais para operações de trading e comex.",
    diff4_title: "Soluções Integradas",
    diff4_desc: "Do subsolo ao mercado: cobrimos toda a cadeia de valor do setor de petróleo e gás com uma abordagem única.",
    services_tag: "O que fazemos",
    services_title: "Serviços Especializados",
    services_sub: "Soluções completas para os desafios mais complexos da indústria.",
    tab_eng: "Engenharia & Consultoria",
    tab_geo: "Geologia & Geofísica",
    tab_biz: "Desenvolvimento de Negócios",
    tab_trade: "Trading Services",
    tab_comex: "Comex Services",
    eng_title: "Engenharia & Consultoria",
    eng_intro: "Em parceria estratégica com a Catu Consultoria, oferecemos experiência nacional e internacional com mais de 35 anos na indústria.",
    eng_1: "Curvas de produção e estimativas de recursos contingentes",
    eng_2: "Estimativa determinística e probabilística de volumes de hidrocarbonetos",
    eng_3: "Planos de desenvolvimento de reservatórios e campos",
    eng_4: "Revitalização de campos maduros de petróleo",
    eng_5: "Estimativas de reservas (SEC e SPE)",
    eng_6: "Aquisição e interpretação de dados de reservatórios",
    eng_7: "Estudos de reservatórios",
    eng_8: "Avaliação econômica de campos, reservatórios e projetos",
    eng_9: "Avaliação completa de ativos de petróleo",
    eng_10: "Projetos de perfuração, completação, reentrada e abandono de poços",
    eng_11: "Projetos de elevação e escoamento",
    eng_12: "Procurement Técnico",
    eng_extra: "Otimização de operações · Análise de risco · Procurement especializado",
    geo_title: "Geologia & Geofísica",
    geo_intro: "Expertise completa em interpretação sísmica, modelagem geológica e avaliação petrofísica para maximizar o potencial dos seus ativos.",
    geo_1: "Planejamento de levantamento sísmico",
    geo_2: "Suporte ao processamento sísmico",
    geo_3: "Interpretação sísmica",
    geo_4: "Análise de atributos sísmicos",
    geo_5: "Análise de bacias sedimentares",
    geo_6: "Mapeamentos regionais",
    geo_7: "Identificação e avaliação de plays, leads e prospectos",
    geo_8: "Análises determinísticas e probabilísticas de parâmetros petrofísicos",
    geo_9: "Modelos geológicos 2D e 3D de reservatórios de óleo e gás",
    biz_title: "Desenvolvimento de Negócios",
    biz_intro: "Estratégias para expandir sua presença no mercado, construir parcerias sólidas e identificar novas oportunidades de crescimento.",
    biz_1: "Prospecção de clientes e novos leads",
    biz_2: "Parcerias estratégicas para benefício mútuo",
    biz_3: "Análise de mercado: tendências, concorrência e oportunidades",
    biz_4: "Modelagem de negócios: novos produtos, canais e fontes de receita",
    trade_title: "Trading Services",
    trade_intro: "Soluções completas de comércio internacional, desde o sourcing até a distribuição final dos produtos.",
    trade_1: "Sourcing de produtos e fornecedores",
    trade_2: "Inspeções de qualidade nas origens dos exportadores",
    trade_3: "Importação por encomenda",
    trade_4: "Importação por conta e ordem",
    trade_5: "Representações de produtos e marcas",
    trade_6: "Comercialização de produtos",
    trade_7: "Assessoria aduaneira",
    trade_8: "Armazenagem e distribuição",
    comex_title: "Comex Services",
    comex_intro: "Logística internacional completa — aéreo, marítimo e rodoviário — com desembaraço aduaneiro eficiente.",
    comex_air_title: "Aéreo",
    comex_air_desc: "Agentes ao redor do globo consolidando e embarcando suas cargas com agilidade e segurança.",
    comex_sea_title: "Marítimo",
    comex_sea_desc: "Contratos com os principais armadores em todos os portos do mundo, agilizando seu frete marítimo.",
    comex_road_title: "Rodoviário",
    comex_road_desc: "Soluções de transporte doméstico para qualquer tipo de carga: expressa, dedicada, consolidada ou projeto.",
    comex_customs_title: "Desembaraço Aduaneiro",
    comex_customs_desc: "Análise completa do processo logístico, NCM, alíquotas e leis aduaneiras para um desembaraço eficiente.",
    clients_tag: "Quem confia em nós",
    clients_title: "Nossos Clientes",
    clients_sub: "Empresas líderes da indústria de energia que confiam na EZO Oilfield Solutions.",
    contact_tag: "Entre em Contato",
    contact_title: "Vamos Trabalhar Juntos",
    contact_sub: "Fale diretamente com nosso CEO para saber como a EZO pode gerar valor para o seu negócio.",
    contact_whatsapp: "WhatsApp / Telefone",
    contact_email_ceo: "E-mail CEO",
    contact_email_sales: "E-mail Comercial",
    form_title: "Envie uma Mensagem",
    form_name: "Nome",
    form_company: "Empresa",
    form_email: "E-mail",
    form_subject: "Assunto",
    form_select: "Selecione um serviço...",
    form_message: "Mensagem",
    form_send: "Enviar Mensagem",
    form_success: "Abrindo seu cliente de e-mail...",
    footer_tagline: "Tecnologia e Inovação na Indústria de Petróleo & Gás",
    footer_services: "Serviços",
    footer_contact: "Contato",
    footer_rights: "Todos os direitos reservados.",
    toast_copied: "Número copiado!",
  },
  en: {
    lang_label: "Language:",
    nav_about: "About",
    nav_differentials: "Why EZO",
    nav_services: "Services",
    nav_clients: "Clients",
    nav_contact: "Contact",
    hero_eyebrow: "Oil & Gas · Technology & Innovation",
    hero_sub: "Specialized Consulting for the Oil & Gas Industry",
    hero_cta1: "Our Services",
    hero_cta2: "Get in Touch",
    scroll_hint: "scroll",
    about_tag: "Who We Are",
    about_title: "Our Mission",
    about_desc: "To create innovative solutions that solve complex challenges, improving our clients' experience and generating value in the oil and gas industry.",
    value1_title: "Creativity & Disruptive Thinking",
    value1_desc: "We encourage unconventional solutions and the courage to break with the status quo.",
    value2_title: "Excellence",
    value2_desc: "We are committed to delivering high-quality solutions with constant dedication.",
    value3_title: "Agility & Adaptability",
    value3_desc: "We learn quickly and respond efficiently to a constantly changing environment.",
    stat1: "Years of Experience",
    stat2: "Active Clients",
    stat3: "Service Areas",
    stat4: "Commitment",
    diff_tag: "Why EZO",
    diff_title: "Our Differentials",
    diff_sub: "The only consultancy integrating Engineering, Geology, Trading and Comex under one roof.",
    diff1_title: "35+ Years in the Market",
    diff1_desc: "Decades of hands-on experience in the Brazilian and international oil and gas industry.",
    diff2_title: "Multidisciplinary Team",
    diff2_desc: "Engineers, geologists, foreign trade and business development specialists in a single partnership.",
    diff3_title: "Global Reach",
    diff3_desc: "Network of agents and strategic partners in international markets for trading and comex operations.",
    diff4_title: "Integrated Solutions",
    diff4_desc: "From subsurface to market: we cover the entire oil and gas value chain with a unique approach.",
    services_tag: "What We Do",
    services_title: "Specialized Services",
    services_sub: "Comprehensive solutions for the most complex industry challenges.",
    tab_eng: "Engineering & Consulting",
    tab_geo: "Geology & Geophysics",
    tab_biz: "Business Development",
    tab_trade: "Trading Services",
    tab_comex: "Comex Services",
    eng_title: "Engineering & Consulting",
    eng_intro: "In strategic partnership with Catu Consultoria, we offer national and international expertise with over 35 years in the industry.",
    eng_1: "Production curves and contingent resource estimates",
    eng_2: "Deterministic and probabilistic hydrocarbon volume estimation",
    eng_3: "Reservoir and field development plans",
    eng_4: "Revitalization of mature oil fields",
    eng_5: "Reserve estimates (SEC and SPE)",
    eng_6: "Acquisition and interpretation of reservoir data",
    eng_7: "Reservoir studies",
    eng_8: "Economic evaluation of fields, reservoirs and projects",
    eng_9: "Complete evaluation of oil assets",
    eng_10: "Drilling, completion, re-entry and well abandonment projects",
    eng_11: "Lifting and flow projects",
    eng_12: "Technical Procurement",
    eng_extra: "Operations optimization · Risk analysis · Specialized procurement",
    geo_title: "Geology & Geophysics",
    geo_intro: "Complete expertise in seismic interpretation, geological modeling and petrophysical evaluation to maximize asset potential.",
    geo_1: "Seismic survey acquisition planning",
    geo_2: "Seismic processing support",
    geo_3: "Seismic interpretation",
    geo_4: "Seismic attribute analysis",
    geo_5: "Sedimentary basin analysis",
    geo_6: "Regional mapping",
    geo_7: "Identification and evaluation of plays, leads and prospects",
    geo_8: "Deterministic and probabilistic analysis of petrophysical parameters",
    geo_9: "2D and 3D geological models of oil and gas reservoirs",
    biz_title: "Business Development",
    biz_intro: "Strategies to expand your market presence, build solid partnerships and identify new growth opportunities.",
    biz_1: "Client prospecting and new leads",
    biz_2: "Strategic partnerships for mutual benefit",
    biz_3: "Market analysis: trends, competition and opportunities",
    biz_4: "Business modeling: new products, channels and revenue sources",
    trade_title: "Trading Services",
    trade_intro: "Complete international trade solutions, from sourcing to final distribution of products.",
    trade_1: "Product and supplier sourcing",
    trade_2: "Quality inspections at exporter origins",
    trade_3: "Import on order",
    trade_4: "Import on behalf and order",
    trade_5: "Product and brand representation",
    trade_6: "Product commercialization",
    trade_7: "Customs advisory",
    trade_8: "Storage and distribution",
    comex_title: "Comex Services",
    comex_intro: "Complete international logistics — air, sea and road — with efficient customs clearance.",
    comex_air_title: "Air",
    comex_air_desc: "Agents around the globe consolidating and shipping your cargo with agility and safety.",
    comex_sea_title: "Maritime",
    comex_sea_desc: "Contracts with major shipowners at all ports worldwide, streamlining your maritime freight.",
    comex_road_title: "Road",
    comex_road_desc: "Domestic transport solutions for any type of cargo: express, dedicated, consolidated or project.",
    comex_customs_title: "Customs Clearance",
    comex_customs_desc: "Complete analysis of the logistics process, NCM codes, tariffs and customs laws for efficient clearance.",
    clients_tag: "Who Trusts Us",
    clients_title: "Our Clients",
    clients_sub: "Leading energy industry companies that trust EZO Oilfield Solutions.",
    contact_tag: "Get In Touch",
    contact_title: "Let's Work Together",
    contact_sub: "Speak directly with our CEO to learn how EZO can generate value for your business.",
    contact_whatsapp: "WhatsApp / Phone",
    contact_email_ceo: "CEO Email",
    contact_email_sales: "Sales Email",
    form_title: "Send a Message",
    form_name: "Name",
    form_company: "Company",
    form_email: "Email",
    form_subject: "Subject",
    form_select: "Select a service...",
    form_message: "Message",
    form_send: "Send Message",
    form_success: "Opening your email client...",
    footer_tagline: "Technology and Innovation in the Oil & Gas Industry",
    footer_services: "Services",
    footer_contact: "Contact",
    footer_rights: "All rights reserved.",
    toast_copied: "Number copied!",
  },
  es: {
    lang_label: "Idioma:",
    nav_about: "Sobre",
    nav_differentials: "Por qué EZO",
    nav_services: "Servicios",
    nav_clients: "Clientes",
    nav_contact: "Contacto",
    hero_eyebrow: "Petróleo & Gas · Tecnología & Innovación",
    hero_sub: "Consultoría Especializada para la Industria del Petróleo y Gas",
    hero_cta1: "Nuestros Servicios",
    hero_cta2: "Contáctenos",
    scroll_hint: "scroll",
    about_tag: "Quiénes Somos",
    about_title: "Nuestra Misión",
    about_desc: "Crear soluciones innovadoras que resuelvan desafíos complejos, mejorando la experiencia de nuestros clientes y generando valor en la industria del petróleo y gas.",
    value1_title: "Creatividad & Pensamiento Disruptivo",
    value1_desc: "Fomentamos soluciones no convencionales y el coraje para romper con el status quo.",
    value2_title: "Excelencia",
    value2_desc: "Nos comprometemos a entregar soluciones de alta calidad con dedicación constante.",
    value3_title: "Agilidad & Adaptabilidad",
    value3_desc: "Aprendemos rápidamente y respondemos con eficiencia en un entorno en constante cambio.",
    stat1: "Años de Experiencia",
    stat2: "Clientes Activos",
    stat3: "Áreas de Servicio",
    stat4: "Compromiso",
    diff_tag: "Por qué EZO",
    diff_title: "Nuestros Diferenciales",
    diff_sub: "La única consultoría que integra Ingeniería, Geología, Trading y Comex bajo un mismo techo.",
    diff1_title: "35+ Años en el Mercado",
    diff1_desc: "Décadas de experiencia práctica en la industria de petróleo y gas nacional e internacional.",
    diff2_title: "Equipo Multidisciplinario",
    diff2_desc: "Ingenieros, geólogos, especialistas en comercio exterior y desarrollo de negocios en una sola alianza.",
    diff3_title: "Alcance Global",
    diff3_desc: "Red de agentes y socios estratégicos en mercados internacionales para operaciones de trading y comex.",
    diff4_title: "Soluciones Integradas",
    diff4_desc: "Del subsuelo al mercado: cubrimos toda la cadena de valor del sector de petróleo y gas con un enfoque único.",
    services_tag: "Lo que hacemos",
    services_title: "Servicios Especializados",
    services_sub: "Soluciones completas para los desafíos más complejos de la industria.",
    tab_eng: "Ingeniería & Consultoría",
    tab_geo: "Geología & Geofísica",
    tab_biz: "Desarrollo de Negocios",
    tab_trade: "Trading Services",
    tab_comex: "Comex Services",
    eng_title: "Ingeniería & Consultoría",
    eng_intro: "En alianza estratégica con Catu Consultoria, ofrecemos experiencia nacional e internacional con más de 35 años en la industria.",
    eng_1: "Curvas de producción y estimaciones de recursos contingentes",
    eng_2: "Estimación determinística y probabilística de volúmenes de hidrocarburos",
    eng_3: "Planes de desarrollo de reservorios y campos",
    eng_4: "Revitalización de campos petroleros maduros",
    eng_5: "Estimaciones de reservas (SEC y SPE)",
    eng_6: "Adquisición e interpretación de datos de reservorios",
    eng_7: "Estudios de reservorios",
    eng_8: "Evaluación económica de campos, reservorios y proyectos",
    eng_9: "Evaluación completa de activos petroleros",
    eng_10: "Proyectos de perforación, completación, reentrada y abandono de pozos",
    eng_11: "Proyectos de elevación y flujo",
    eng_12: "Procurement Técnico",
    eng_extra: "Optimización de operaciones · Análisis de riesgo · Procurement especializado",
    geo_title: "Geología & Geofísica",
    geo_intro: "Experiencia completa en interpretación sísmica, modelado geológico y evaluación petrofísica para maximizar el potencial de sus activos.",
    geo_1: "Planificación de adquisición de levantamiento sísmico",
    geo_2: "Soporte al procesamiento sísmico",
    geo_3: "Interpretación sísmica",
    geo_4: "Análisis de atributos sísmicos",
    geo_5: "Análisis de cuencas sedimentarias",
    geo_6: "Cartografías regionales",
    geo_7: "Identificación y evaluación de plays, leads y prospectos",
    geo_8: "Análisis determinísticos y probabilísticos de parámetros petrofísicos",
    geo_9: "Modelos geológicos 2D y 3D de reservorios de petróleo y gas",
    biz_title: "Desarrollo de Negocios",
    biz_intro: "Estrategias para expandir su presencia en el mercado, construir alianzas sólidas e identificar nuevas oportunidades de crecimiento.",
    biz_1: "Prospección de clientes y nuevos leads",
    biz_2: "Alianzas estratégicas para beneficio mutuo",
    biz_3: "Análisis de mercado: tendencias, competencia y oportunidades",
    biz_4: "Modelado de negocios: nuevos productos, canales y fuentes de ingresos",
    trade_title: "Trading Services",
    trade_intro: "Soluciones completas de comercio internacional, desde el sourcing hasta la distribución final de los productos.",
    trade_1: "Sourcing de productos y proveedores",
    trade_2: "Inspecciones de calidad en los orígenes de los exportadores",
    trade_3: "Importación por encargo",
    trade_4: "Importación por cuenta y orden",
    trade_5: "Representaciones de productos y marcas",
    trade_6: "Comercialización de productos",
    trade_7: "Asesoría aduanera",
    trade_8: "Almacenamiento y distribución",
    comex_title: "Comex Services",
    comex_intro: "Logística internacional completa — aéreo, marítimo y terrestre — con despacho aduanero eficiente.",
    comex_air_title: "Aéreo",
    comex_air_desc: "Agentes en todo el mundo consolidando y enviando su carga con agilidad y seguridad.",
    comex_sea_title: "Marítimo",
    comex_sea_desc: "Contratos con los principales armadores en todos los puertos del mundo, agilizando su flete marítimo.",
    comex_road_title: "Terrestre",
    comex_road_desc: "Soluciones de transporte doméstico para cualquier tipo de carga: expresa, dedicada, consolidada o proyecto.",
    comex_customs_title: "Despacho Aduanero",
    comex_customs_desc: "Análisis completo del proceso logístico, NCM, aranceles y leyes aduaneras para un despacho eficiente.",
    clients_tag: "Quiénes confían en nosotros",
    clients_title: "Nuestros Clientes",
    clients_sub: "Empresas líderes de la industria energética que confían en EZO Oilfield Solutions.",
    contact_tag: "Póngase en Contacto",
    contact_title: "Trabajemos Juntos",
    contact_sub: "Hable directamente con nuestro CEO para saber cómo EZO puede generar valor para su negocio.",
    contact_whatsapp: "WhatsApp / Teléfono",
    contact_email_ceo: "Email CEO",
    contact_email_sales: "Email Comercial",
    form_title: "Envíe un Mensaje",
    form_name: "Nombre",
    form_company: "Empresa",
    form_email: "Correo electrónico",
    form_subject: "Asunto",
    form_select: "Seleccione un servicio...",
    form_message: "Mensaje",
    form_send: "Enviar Mensaje",
    form_success: "¡Abriendo su cliente de correo!",
    footer_tagline: "Tecnología e Innovación en la Industria del Petróleo y Gas",
    footer_services: "Servicios",
    footer_contact: "Contacto",
    footer_rights: "Todos los derechos reservados.",
    toast_copied: "¡Número copiado!",
  },
  fr: {
    lang_label: "Langue :",
    nav_about: "À propos",
    nav_differentials: "Pourquoi EZO",
    nav_services: "Services",
    nav_clients: "Clients",
    nav_contact: "Contact",
    hero_eyebrow: "Pétrole & Gaz · Technologie & Innovation",
    hero_sub: "Conseil Spécialisé pour l'Industrie Pétrolière et Gazière",
    hero_cta1: "Nos Services",
    hero_cta2: "Contactez-nous",
    scroll_hint: "défiler",
    about_tag: "Qui Sommes-Nous",
    about_title: "Notre Mission",
    about_desc: "Créer des solutions innovantes qui résolvent des défis complexes, améliorant l'expérience de nos clients et générant de la valeur dans l'industrie pétrolière et gazière.",
    value1_title: "Créativité & Pensée Disruptive",
    value1_desc: "Nous encourageons des solutions non conventionnelles et le courage de rompre avec le statu quo.",
    value2_title: "Excellence",
    value2_desc: "Nous nous engageons à fournir des solutions de haute qualité avec un dévouement constant.",
    value3_title: "Agilité & Adaptabilité",
    value3_desc: "Nous apprenons rapidement et répondons efficacement dans un environnement en constante évolution.",
    stat1: "Années d'Expérience",
    stat2: "Clients Actifs",
    stat3: "Domaines de Service",
    stat4: "Engagement",
    diff_tag: "Pourquoi EZO",
    diff_title: "Nos Différentiels",
    diff_sub: "Le seul cabinet intégrant Ingénierie, Géologie, Trading et Comex sous un même toit.",
    diff1_title: "35+ Ans de Marché",
    diff1_desc: "Des décennies d'expérience pratique dans l'industrie pétrolière et gazière nationale et internationale.",
    diff2_title: "Équipe Multidisciplinaire",
    diff2_desc: "Ingénieurs, géologues, spécialistes en commerce international et développement commercial réunis.",
    diff3_title: "Portée Mondiale",
    diff3_desc: "Réseau d'agents et de partenaires stratégiques sur les marchés internationaux pour le trading et le comex.",
    diff4_title: "Solutions Intégrées",
    diff4_desc: "Du sous-sol au marché : nous couvrons toute la chaîne de valeur du secteur pétrolier et gazier.",
    services_tag: "Ce que nous faisons",
    services_title: "Services Spécialisés",
    services_sub: "Des solutions complètes pour les défis les plus complexes de l'industrie.",
    tab_eng: "Ingénierie & Conseil",
    tab_geo: "Géologie & Géophysique",
    tab_biz: "Développement Commercial",
    tab_trade: "Services de Trading",
    tab_comex: "Services Comex",
    eng_title: "Ingénierie & Conseil",
    eng_intro: "En partenariat stratégique avec Catu Consultoria, nous offrons une expertise nationale et internationale avec plus de 35 ans dans l'industrie.",
    eng_1: "Courbes de production et estimations de ressources contingentes",
    eng_2: "Estimation déterministe et probabiliste des volumes d'hydrocarbures",
    eng_3: "Plans de développement de réservoirs et de champs",
    eng_4: "Revitalisation de champs pétroliers matures",
    eng_5: "Estimations de réserves (SEC et SPE)",
    eng_6: "Acquisition et interprétation de données de réservoir",
    eng_7: "Études de réservoirs",
    eng_8: "Évaluation économique de champs, réservoirs et projets",
    eng_9: "Évaluation complète des actifs pétroliers",
    eng_10: "Projets de forage, complétion, réentrée et abandon de puits",
    eng_11: "Projets de levage et d'écoulement",
    eng_12: "Approvisionnement Technique",
    eng_extra: "Optimisation des opérations · Analyse des risques · Approvisionnement spécialisé",
    geo_title: "Géologie & Géophysique",
    geo_intro: "Expertise complète en interprétation sismique, modélisation géologique et évaluation pétrophysique.",
    geo_1: "Planification de l'acquisition du levé sismique",
    geo_2: "Soutien au traitement sismique",
    geo_3: "Interprétation sismique",
    geo_4: "Analyse des attributs sismiques",
    geo_5: "Analyse des bassins sédimentaires",
    geo_6: "Cartographies régionales",
    geo_7: "Identification et évaluation de plays, leads et prospects",
    geo_8: "Analyses déterministes et probabilistes des paramètres pétrophysiques",
    geo_9: "Modèles géologiques 2D et 3D de réservoirs de pétrole et de gaz",
    biz_title: "Développement Commercial",
    biz_intro: "Stratégies pour élargir votre présence sur le marché, établir des partenariats solides et identifier de nouvelles opportunités.",
    biz_1: "Prospection de clients et nouveaux leads",
    biz_2: "Partenariats stratégiques à bénéfice mutuel",
    biz_3: "Analyse de marché : tendances, concurrence et opportunités",
    biz_4: "Modélisation commerciale : nouveaux produits, canaux et sources de revenus",
    trade_title: "Services de Trading",
    trade_intro: "Solutions complètes de commerce international, du sourcing à la distribution finale des produits.",
    trade_1: "Sourcing de produits et fournisseurs",
    trade_2: "Inspections qualité aux origines des exportateurs",
    trade_3: "Importation sur commande",
    trade_4: "Importation pour compte et ordre",
    trade_5: "Représentations de produits et marques",
    trade_6: "Commercialisation de produits",
    trade_7: "Conseil douanier",
    trade_8: "Entreposage et distribution",
    comex_title: "Services Comex",
    comex_intro: "Logistique internationale complète — aérien, maritime et routier — avec dédouanement efficace.",
    comex_air_title: "Aérien",
    comex_air_desc: "Des agents dans le monde entier consolidant et expédiant vos marchandises rapidement.",
    comex_sea_title: "Maritime",
    comex_sea_desc: "Contrats avec les principaux armateurs dans tous les ports du monde.",
    comex_road_title: "Routier",
    comex_road_desc: "Solutions de transport domestique pour tout type de fret : express, dédié, consolidé ou projet.",
    comex_customs_title: "Dédouanement",
    comex_customs_desc: "Analyse complète du processus logistique, nomenclature, droits de douane et lois douanières.",
    clients_tag: "Qui nous fait confiance",
    clients_title: "Nos Clients",
    clients_sub: "Des entreprises leaders de l'industrie énergétique qui font confiance à EZO Oilfield Solutions.",
    contact_tag: "Prenez Contact",
    contact_title: "Travaillons Ensemble",
    contact_sub: "Parlez directement avec notre PDG pour savoir comment EZO peut générer de la valeur pour votre activité.",
    contact_whatsapp: "WhatsApp / Téléphone",
    contact_email_ceo: "Email PDG",
    contact_email_sales: "Email Commercial",
    form_title: "Envoyez un Message",
    form_name: "Nom",
    form_company: "Entreprise",
    form_email: "E-mail",
    form_subject: "Sujet",
    form_select: "Sélectionnez un service...",
    form_message: "Message",
    form_send: "Envoyer",
    form_success: "Ouverture de votre client de messagerie...",
    footer_tagline: "Technologie et Innovation dans l'Industrie Pétrolière et Gazière",
    footer_services: "Services",
    footer_contact: "Contact",
    footer_rights: "Tous droits réservés.",
    toast_copied: "Numéro copié !",
  },
  zh: {
    lang_label: "语言：",
    nav_about: "关于我们",
    nav_differentials: "为何选择EZO",
    nav_services: "服务",
    nav_clients: "客户",
    nav_contact: "联系我们",
    hero_eyebrow: "石油与天然气 · 技术与创新",
    hero_sub: "石油与天然气行业专业咨询",
    hero_cta1: "我们的服务",
    hero_cta2: "联系我们",
    scroll_hint: "滚动",
    about_tag: "关于我们",
    about_title: "我们的使命",
    about_desc: "创造创新解决方案，解决复杂挑战，提升客户体验，在石油和天然气行业创造价值。",
    value1_title: "创造力与颠覆性思维",
    value1_desc: "我们鼓励非常规解决方案和打破现状的勇气。",
    value2_title: "卓越",
    value2_desc: "我们致力于以持续的奉献精神提供高质量的解决方案。",
    value3_title: "敏捷性与适应性",
    value3_desc: "我们快速学习，并在不断变化的环境中高效响应。",
    stat1: "年经验",
    stat2: "活跃客户",
    stat3: "服务领域",
    stat4: "承诺",
    diff_tag: "为何选择EZO",
    diff_title: "我们的优势",
    diff_sub: "唯一整合工程、地质、贸易和外贸服务的咨询公司。",
    diff1_title: "35年以上市场经验",
    diff1_desc: "数十年国内外石油天然气行业实践经验。",
    diff2_title: "多学科团队",
    diff2_desc: "工程师、地质学家、外贸及业务发展专家汇聚一堂。",
    diff3_title: "全球布局",
    diff3_desc: "遍布国际市场的代理商和战略合作伙伴网络。",
    diff4_title: "一体化解决方案",
    diff4_desc: "从地下到市场：以独特方式覆盖油气行业整个价值链。",
    services_tag: "我们的工作",
    services_title: "专业服务",
    services_sub: "为行业最复杂的挑战提供全面解决方案。",
    tab_eng: "工程与咨询",
    tab_geo: "地质与地球物理",
    tab_biz: "业务发展",
    tab_trade: "贸易服务",
    tab_comex: "外贸服务",
    eng_title: "工程与咨询",
    eng_intro: "与Catu Consultoria战略合作，提供35年以上国内外行业经验。",
    eng_1: "生产曲线和或然资源估算",
    eng_2: "确定性和概率性油气体积估算",
    eng_3: "储层和油田开发方案",
    eng_4: "老油田振兴",
    eng_5: "储量估算（SEC和SPE）",
    eng_6: "储层数据采集与解释",
    eng_7: "储层研究",
    eng_8: "油田、储层和项目经济评价",
    eng_9: "石油资产全面评估",
    eng_10: "钻井、完井、侧钻和废弃项目",
    eng_11: "举升和流动项目",
    eng_12: "技术采购",
    eng_extra: "运营优化 · 风险分析 · 专业采购",
    geo_title: "地质与地球物理",
    geo_intro: "地震解释、地质建模和岩石物理评价的完整专业知识。",
    geo_1: "地震勘探采集规划",
    geo_2: "地震处理支持",
    geo_3: "地震解释",
    geo_4: "地震属性分析",
    geo_5: "沉积盆地分析",
    geo_6: "区域填图",
    geo_7: "成藏、圈闭和远景区识别与评价",
    geo_8: "岩石物理参数确定性和概率性分析",
    geo_9: "油气储层2D和3D地质模型",
    biz_title: "业务发展",
    biz_intro: "扩大市场存在、建立稳固合作关系、识别新增长机会的战略。",
    biz_1: "客户开发和新线索",
    biz_2: "互利战略合作",
    biz_3: "市场分析：趋势、竞争和机遇",
    biz_4: "商业建模：新产品、渠道和收入来源",
    trade_title: "贸易服务",
    trade_intro: "从采购到产品最终分销的完整国际贸易解决方案。",
    trade_1: "产品和供应商采购",
    trade_2: "在出口商原产地进行质量检验",
    trade_3: "订单进口",
    trade_4: "代理进口",
    trade_5: "产品和品牌代理",
    trade_6: "产品商业化",
    trade_7: "海关顾问",
    trade_8: "仓储和配送",
    comex_title: "外贸服务",
    comex_intro: "完整的国际物流——航空、海运和公路——高效清关。",
    comex_air_title: "航空",
    comex_air_desc: "遍布全球的代理商，以敏捷和安全的方式整合和运输您的货物。",
    comex_sea_title: "海运",
    comex_sea_desc: "与全球主要船东签订合同，简化您的海运货运。",
    comex_road_title: "公路",
    comex_road_desc: "任何类型货物的国内运输解决方案：快递、专用、整合或项目货物。",
    comex_customs_title: "清关",
    comex_customs_desc: "对物流流程、税号、关税和海关法律进行全面分析，实现高效清关。",
    clients_tag: "信任我们的客户",
    clients_title: "我们的客户",
    clients_sub: "信任EZO Oilfield Solutions的能源行业领先企业。",
    contact_tag: "联系我们",
    contact_title: "让我们合作",
    contact_sub: "直接与我们的CEO交流，了解EZO如何为您的业务创造价值。",
    contact_whatsapp: "WhatsApp / 电话",
    contact_email_ceo: "CEO邮箱",
    contact_email_sales: "商务邮箱",
    form_title: "发送消息",
    form_name: "姓名",
    form_company: "公司",
    form_email: "电子邮件",
    form_subject: "主题",
    form_select: "选择服务...",
    form_message: "消息",
    form_send: "发送消息",
    form_success: "正在打开您的邮件客户端...",
    footer_tagline: "石油与天然气行业的技术与创新",
    footer_services: "服务",
    footer_contact: "联系方式",
    footer_rights: "版权所有。",
    toast_copied: "号码已复制！",
  },
  ar: {
    lang_label: "اللغة:",
    nav_about: "حول",
    nav_differentials: "لماذا EZO",
    nav_services: "الخدمات",
    nav_clients: "العملاء",
    nav_contact: "اتصل بنا",
    hero_eyebrow: "النفط والغاز · التكنولوجيا والابتكار",
    hero_sub: "استشارات متخصصة لصناعة النفط والغاز",
    hero_cta1: "خدماتنا",
    hero_cta2: "تواصل معنا",
    scroll_hint: "تمرير",
    about_tag: "من نحن",
    about_title: "مهمتنا",
    about_desc: "إنشاء حلول مبتكرة تحل التحديات المعقدة، وتحسين تجربة عملائنا وتوليد القيمة في صناعة النفط والغاز.",
    value1_title: "الإبداع والتفكير التخريبي",
    value1_desc: "نشجع الحلول غير التقليدية والشجاعة لكسر الوضع الراهن.",
    value2_title: "التميز",
    value2_desc: "نلتزم بتقديم حلول عالية الجودة بتفانٍ مستمر.",
    value3_title: "الرشاقة والقدرة على التكيف",
    value3_desc: "نتعلم بسرعة ونستجيب بكفاءة في بيئة متغيرة باستمرار.",
    stat1: "سنة خبرة",
    stat2: "عملاء نشطون",
    stat3: "مجالات الخدمة",
    stat4: "الالتزام",
    diff_tag: "لماذا EZO",
    diff_title: "مميزاتنا",
    diff_sub: "الشركة الاستشارية الوحيدة التي تدمج الهندسة والجيولوجيا والتجارة والاستيراد تحت سقف واحد.",
    diff1_title: "35+ عامًا في السوق",
    diff1_desc: "عقود من الخبرة العملية في صناعة النفط والغاز الوطنية والدولية.",
    diff2_title: "فريق متعدد التخصصات",
    diff2_desc: "مهندسون وجيولوجيون ومتخصصون في التجارة الخارجية وتطوير الأعمال.",
    diff3_title: "انتشار عالمي",
    diff3_desc: "شبكة من الوكلاء والشركاء الاستراتيجيين في الأسواق الدولية.",
    diff4_title: "حلول متكاملة",
    diff4_desc: "من الباطن إلى السوق: نغطي سلسلة القيمة الكاملة لقطاع النفط والغاز.",
    services_tag: "ما نقوم به",
    services_title: "خدمات متخصصة",
    services_sub: "حلول شاملة لأكثر التحديات تعقيدًا في الصناعة.",
    tab_eng: "الهندسة والاستشارات",
    tab_geo: "الجيولوجيا والجيوفيزياء",
    tab_biz: "تطوير الأعمال",
    tab_trade: "خدمات التداول",
    tab_comex: "خدمات التجارة الخارجية",
    eng_title: "الهندسة والاستشارات",
    eng_intro: "بالشراكة الاستراتيجية مع Catu Consultoria، نقدم خبرة وطنية ودولية تمتد لأكثر من 35 عامًا.",
    eng_1: "منحنيات الإنتاج وتقديرات الموارد المحتملة",
    eng_2: "التقدير الحتمي والاحتمالي لأحجام الهيدروكربونات",
    eng_3: "خطط تطوير الخزانات والحقول",
    eng_4: "تنشيط حقول النفط الناضجة",
    eng_5: "تقديرات الاحتياطيات (SEC و SPE)",
    eng_6: "اقتناء وتفسير بيانات الخزانات",
    eng_7: "دراسات الخزانات",
    eng_8: "التقييم الاقتصادي للحقول والخزانات والمشاريع",
    eng_9: "التقييم الشامل لأصول النفط",
    eng_10: "مشاريع الحفر والإكمال وإعادة الدخول والتخلي عن الآبار",
    eng_11: "مشاريع الرفع والتدفق",
    eng_12: "المشتريات الفنية",
    eng_extra: "تحسين العمليات · تحليل المخاطر · المشتريات المتخصصة",
    geo_title: "الجيولوجيا والجيوفيزياء",
    geo_intro: "خبرة كاملة في التفسير الزلزالي والنمذجة الجيولوجية والتقييم البتروفيزيائي.",
    geo_1: "تخطيط اقتناء المسح الزلزالي",
    geo_2: "دعم المعالجة الزلزالية",
    geo_3: "التفسير الزلزالي",
    geo_4: "تحليل السمات الزلزالية",
    geo_5: "تحليل الأحواض الرسوبية",
    geo_6: "رسم الخرائط الإقليمية",
    geo_7: "تحديد وتقييم المناطق الواعدة",
    geo_8: "التحليل الحتمي والاحتمالي للمعاملات البتروفيزيائية",
    geo_9: "نماذج جيولوجية ثنائية وثلاثية الأبعاد",
    biz_title: "تطوير الأعمال",
    biz_intro: "استراتيجيات لتوسيع حضورك في السوق وبناء شراكات متينة وتحديد فرص نمو جديدة.",
    biz_1: "التنقيب عن العملاء والعملاء المحتملين",
    biz_2: "شراكات استراتيجية للمنفعة المتبادلة",
    biz_3: "تحليل السوق: الاتجاهات والمنافسة والفرص",
    biz_4: "نمذجة الأعمال: منتجات وقنوات ومصادر إيرادات جديدة",
    trade_title: "خدمات التداول",
    trade_intro: "حلول تجارة دولية شاملة، من المصادر إلى التوزيع النهائي.",
    trade_1: "مصادر المنتجات والموردين",
    trade_2: "فحوصات الجودة في منابع المصدرين",
    trade_3: "الاستيراد بالطلب",
    trade_4: "الاستيراد لحساب وأمر الغير",
    trade_5: "تمثيل المنتجات والعلامات التجارية",
    trade_6: "تسويق المنتجات",
    trade_7: "الاستشارات الجمركية",
    trade_8: "التخزين والتوزيع",
    comex_title: "خدمات التجارة الخارجية",
    comex_intro: "لوجستيات دولية كاملة — جوية وبحرية وبرية — مع تخليص جمركي فعّال.",
    comex_air_title: "جوي",
    comex_air_desc: "وكلاء في جميع أنحاء العالم يجمعون ويشحنون بضائعك بسرعة وأمان.",
    comex_sea_title: "بحري",
    comex_sea_desc: "عقود مع كبار الملاك البحريين في جميع موانئ العالم.",
    comex_road_title: "بري",
    comex_road_desc: "حلول نقل محلية لأي نوع من البضائع.",
    comex_customs_title: "التخليص الجمركي",
    comex_customs_desc: "تحليل شامل للعملية اللوجستية والتعريفات الجمركية والقوانين.",
    clients_tag: "من يثق بنا",
    clients_title: "عملاؤنا",
    clients_sub: "شركات رائدة في صناعة الطاقة تثق في EZO Oilfield Solutions.",
    contact_tag: "تواصل معنا",
    contact_title: "لنعمل معًا",
    contact_sub: "تحدث مباشرة مع الرئيس التنفيذي لمعرفة كيف يمكن لـ EZO تحقيق قيمة لعملك.",
    contact_whatsapp: "واتساب / هاتف",
    contact_email_ceo: "بريد الرئيس التنفيذي",
    contact_email_sales: "البريد التجاري",
    form_title: "أرسل رسالة",
    form_name: "الاسم",
    form_company: "الشركة",
    form_email: "البريد الإلكتروني",
    form_subject: "الموضوع",
    form_select: "اختر خدمة...",
    form_message: "الرسالة",
    form_send: "إرسال",
    form_success: "جارٍ فتح عميل البريد الإلكتروني...",
    footer_tagline: "التكنولوجيا والابتكار في صناعة النفط والغاز",
    footer_services: "الخدمات",
    footer_contact: "التواصل",
    footer_rights: "جميع الحقوق محفوظة.",
    toast_copied: "تم نسخ الرقم!",
  }
};

function detectLang() {
  const nav = navigator.language || navigator.userLanguage || 'pt';
  const code = nav.toLowerCase().split('-')[0];
  const supported = ['pt', 'en', 'es', 'fr', 'zh', 'ar'];
  return supported.includes(code) ? code : 'en';
}

let currentLang = detectLang();

function setLang(lang) {
  currentLang = lang;
  const t = translations[lang] || translations.pt;

  document.querySelectorAll('[data-i18n]').forEach(el => {
    const key = el.getAttribute('data-i18n');
    if (t[key] !== undefined) {
      if (el.tagName === 'INPUT' || el.tagName === 'TEXTAREA') {
        el.placeholder = t[key];
      } else {
        el.textContent = t[key];
      }
    }
  });

  document.querySelectorAll('[data-i18n-ph]').forEach(el => {
    const key = el.getAttribute('data-i18n-ph');
    if (t[key]) el.placeholder = t[key];
  });

  document.querySelectorAll('.lang-btn').forEach(btn => btn.classList.remove('active'));
  document.querySelector(`.lang-btn[onclick="setLang('${lang}')"]`)?.classList.add('active');

  document.documentElement.setAttribute('lang', lang);

  if (lang === 'ar') {
    document.body.setAttribute('dir', 'rtl');
  } else {
    document.body.removeAttribute('dir');
  }
}

function showTab(tabId) {
  document.querySelectorAll('.tab-content').forEach(c => c.classList.remove('active'));
  document.querySelectorAll('.tab-btn').forEach(b => b.classList.remove('active'));
  const target = document.getElementById('tab-' + tabId);
  if (target) target.classList.add('active');
  const idx = ['engineering','geology','bizdev','trading','comex'].indexOf(tabId);
  const btns = document.querySelectorAll('.tab-btn');
  if (btns[idx]) btns[idx].classList.add('active');
}

function toggleMenu() {
  document.getElementById('main-nav').classList.toggle('open');
}

function submitForm(e) {
  e.preventDefault();
  const name    = document.getElementById('form-name').value.trim();
  const company = document.getElementById('form-company').value.trim();
  const email   = document.getElementById('form-email').value.trim();
  const subject = document.getElementById('form-subject').value;
  const message = document.getElementById('form-message').value.trim();

  if (!name || !email || !message) {
    showToast('Preencha nome, e-mail e mensagem.');
    return;
  }

  const mailSubject = encodeURIComponent((subject || 'Contato') + (company ? ' — ' + company : ''));
  const mailBody    = encodeURIComponent(
    `Nome: ${name}\nEmpresa: ${company}\nE-mail: ${email}\n\n${message}`
  );
  const mailto = `mailto:vendas@ezosolutions.com.br?subject=${mailSubject}&body=${mailBody}`;

  document.getElementById('contact-form').style.display = 'none';
  document.getElementById('form-success').style.display  = 'block';
  setTimeout(() => { window.location.href = mailto; }, 500);
}

function showToast(msg) {
  const toast = document.getElementById('toast');
  toast.textContent = msg;
  toast.classList.add('show');
  setTimeout(() => toast.classList.remove('show'), 2800);
}

const sections = ['about','differentials','services','clients','contact'];

window.addEventListener('scroll', () => {
  const header = document.getElementById('header');
  header.classList.toggle('scrolled', window.scrollY > 60);

  const scrollMid = window.scrollY + window.innerHeight / 3;
  let active = '';
  sections.forEach(id => {
    const el = document.getElementById(id);
    if (el && el.offsetTop <= scrollMid) active = id;
  });
  document.querySelectorAll('#main-nav a').forEach(a => {
    const href = a.getAttribute('href');
    if (href === '#' + active) {
      a.classList.add('active');
    } else {
      a.classList.remove('active');
    }
  });
});

document.querySelectorAll('a[href^="#"]').forEach(link => {
  link.addEventListener('click', () => {
    document.getElementById('main-nav')?.classList.remove('open');
  });
});

const revealObserver = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('visible');
    }
  });
}, { threshold: 0.05, rootMargin: '0px 0px -40px 0px' });

document.querySelectorAll('.reveal-section').forEach(el => {
  revealObserver.observe(el);
});

const cardObserver = new IntersectionObserver((entries) => {
  entries.forEach((entry, i) => {
    if (entry.isIntersecting) {
      setTimeout(() => entry.target.classList.add('visible'), i * 80);
    }
  });
}, { threshold: 0.05, rootMargin: '0px 0px -20px 0px' });

document.querySelectorAll('.stat-card, .value-item, .client-card, .comex-card, .sitem, .diff-card').forEach((el) => {
  el.style.transition = 'opacity 0.55s ease, transform 0.55s ease';
  cardObserver.observe(el);
});

document.addEventListener('DOMContentLoaded', () => {
  setLang(currentLang);

  const checkVisible = () => {
    document.querySelectorAll('.reveal-section').forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight && rect.bottom > 0) {
        el.classList.add('visible');
      }
    });
    document.querySelectorAll('.stat-card, .value-item, .client-card, .comex-card, .sitem, .diff-card').forEach(el => {
      const rect = el.getBoundingClientRect();
      if (rect.top < window.innerHeight && rect.bottom > 0) {
        el.classList.add('visible');
      }
    });
  };

  checkVisible();
  setTimeout(checkVisible, 100);
  setTimeout(checkVisible, 400);
});