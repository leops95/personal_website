---
layout: default
---
<base target="_blank">

## About me

I'm a Research Fellow at the [University of Basel](https://wwz.unibas.ch/en/), where I obtained my PhD in Business and Economics earlier this year. Prior to my doctoral studies, I worked as a Scientific Assistant at [ETH Zürich's Center for Law and Economics](https://lawecon.ethz.ch/). My research interests include:
* Public policy and sustainable development
* The EU Emissions Trading System
* Emotional appeals in US politics and media

Recently, I have joined [Galenica](https://www.galenica.com/en/) in Bern as a Data Analyst.
<br/>
<br/>
<br/>

## Publications

### Peer-reviewed

<b class="pub-title">Figurative and Literal Language in US Governor Speeches</b>, Swiss Journal of Economics and Statistics (2026). \
Joint work with <a href="https://dominik-stammbach.github.io/" style="color: inherit; text-decoration: underline;">Dominik Stammbach</a>. \
<button onclick="togglePanel(this,'abs-1')" class="label panel-btn" aria-controls="abs-1">Abstract</button>
<button onclick="window.open('https://doi.org/10.1186/s41937-026-00155-y', '_blank')" class="label">DOI</button>
<button onclick="window.open('https://link.springer.com/content/pdf/10.1186/s41937-026-00155-y.pdf', '_blank')" class="label">URL</button>
<button onclick="window.open('https://media.springernature.com/original/springer-static/esm/art%3A10.1186%2Fs41937-026-00155-y/MediaObjects/41937_2026_155_MOESM2_ESM.zip', '_blank')" class="label">Replication package</button>

<div class="panels">
    <div id="abs-1" class="panel">
    <p>This paper examines figurative expressions, such as metaphors, and their association with emotional language in political rhetoric. We compare figurative and literal language employed by US governors by applying a deep learning-based model to their State of the State speeches from 1995 to 2022. Predictions are clustered into nine socioeconomic topics relevant to policy. We then document their use as part of strategic communication. Our results show that partisanship predicts the types of expressions used. Democratic governors are more likely to use highly figurative expressions when discussing environmental issues compared to their Republican counterparts. In contrast, Republicans use them relatively more when talking about moral values such as freedom and liberty. In addition, we show that figurative language on these topics is associated with more emotional language, with significant heterogeneity among them. These results suggest that figurative language may be used as emotional appeals to discuss key political issues.</p>
    </div>
</div>

<b class="pub-title">Cable News and COVID-19 Vaccine Uptake</b>, Scientific Reports (2022). \
Joint work with <a href="https://goessmann.io/" style="color: inherit; text-decoration: underline;">Christoph Goessmann</a> and <a href="https://sites.google.com/view/matteopinna/" style="color: inherit; text-decoration: underline;">Matteo Pinna</a>.\
<button onclick="togglePanel(this,'abs-2')" class="label panel-btn" aria-controls="abs-2">Abstract</button>
<button onclick="window.open('https://doi.org/10.1038/s41598-022-20350-0', '_blank')" class="label">DOI</button>
<button onclick="window.open('https://www.nature.com/articles/s41598-022-20350-0.pdf', '_blank')" class="label">URL</button>
<button onclick="window.open('https://www.research-collection.ethz.ch/entities/researchdata/873eaebc-8b62-40ac-b8be-db1bcfd3a7d6', '_blank')" class="label">Replication package</button>
<button onclick="togglePanel(this,'media-1')" class="label panel-btn" aria-controls="media-1">Media coverage</button>

<div class="panels">
  <div id="abs-2" class="panel">
    <p>COVID-19 vaccines have reduced infections and hospitalizations across the globe, yet resistance to vaccination remains strong. This paper investigates the role of cable television news in vaccine hesitancy and associated local vaccination rates in the United States. We find that, in the earlier stages of the vaccine roll-out (starting May 2021), higher local viewership of Fox News Channel has been associated with lower local vaccination rates. We can verify that this association is causal using exogenous geographical variation in the channel lineup. The effect is driven by younger individuals (under 65 years of age), for whom COVID-19 has a low mortality risk. Consistent with changes in beliefs about the effectiveness of the vaccine as a mechanism, we find that Fox News increased reported vaccine hesitancy in local survey responses. We can rule out that the effect is due to differences in partisanship, to local health policies, or to local COVID-19 infections or death rates. The other two major television networks, CNN and MSNBC, have no effect. That, in turn, indicates that more differentiated characteristics, like the networks' messaging or tendency for controversy, matter and that the effect of Fox News on COVID-19 vaccine uptake is not due to the general consumption of cable news. We also show that there is no historical effect of Fox News on flu vaccination rates, suggesting that the effect is COVID-19-specific and not driven by general skepticism toward vaccines.</p>
  </div>

  <div id="media-1" class="panel">
    <p>
        <a href="https://cepr.org/voxeu/columns/impact-fox-news-us-covid-19-vaccination-campaign" target="_blank" rel="noopener">CEPR VoxEU Column</a> (Summary)<br/>
        <a href="https://cepr.org/multimedia/how-fox-news-inspired-vaccine-hesitancy" target="_blank" rel="noopener">CEPR VoxTalks Economics</a> (Podcast)<br/>
        <a href="https://www.bloomberg.com/news/articles/2023-03-10/fox-news-content-led-to-covid-vaccine-hesitancy-among-viewers" target="_blank" rel="noopener">Bloomberg</a><sup class="fn">*</sup><br/>
        <a href="https://www.nytimes.com/2022/10/16/opinion/alex-jones-sandy-hook.html" target="_blank" rel="noopener">The New York Times</a><sup class="fn">*</sup><br/>
        <a href="https://www.washingtonpost.com/politics/2022/10/10/vaccines-coronavirus-fox-news/" target="_blank" rel="noopener">The Washington Post</a><br/>
        <a href="https://www.msnbc.com/opinion/connecting-dots-between-covid-vaccine-hesitancy-fox-news-n1276592" target="_blank" rel="noopener">MSNBC</a><br/>
        <a href="https://www.theatlantic.com/politics/archive/2021/08/why-so-many-republicans-wont-get-vaccinated/619659/" target="_blank" rel="noopener">The Atlantic</a><sup class="fn">*</sup>
        <br/><br/>
        <sup>*</sup> <i>Under paywall</i>
    </p>
  </div>
</div>

<script>
function togglePanel(btn, id) {
  const panel = document.getElementById(id);
  const group = panel.closest('.panels');
  const openPanel = group.querySelector('.panel.open');
  const willOpen = !panel.classList.contains('open');

  if (!openPanel || openPanel === panel) {
    panel.classList.toggle('open', willOpen);
    btn.classList.toggle('open', willOpen);
    return;
  }

  const otherBtn = document.querySelector('.panel-btn.open');
  openPanel.classList.remove('open');
  if (otherBtn) otherBtn.classList.remove('open');

  const delay = willOpen ? 400 : 0;
  setTimeout(() => {
    if (willOpen) {
      panel.classList.add('open');
      btn.classList.add('open');
    }
  }, delay);
}
</script>



### Policy reports

<b class="pub-title">Illicit financial flows and sustainable development: Panel-data evidence for Africa</b>, United Nations Conference on Trade and Development (2020). \
Joint work with <a href="https://linkedin.com/in/mcherelrobson1" style="color: inherit; text-decoration: underline;">Milasoa Chérel-Robson</a> and <a href="https://linkedin.com/in/anja-slany-747b0b125" style="color: inherit; text-decoration: underline;">Anja Slany</a>. \
<button onclick="window.open('https://digitallibrary.un.org/record/4041968?v=pdf', '_blank')" class="label">URL</button>
<button onclick="togglePanel(this,'abs-3')" class="label panel-btn" aria-controls="abs-3">Additional content</button>

<div class="panels">
    <div id="abs-3" class="panel">
    <p>This statistical note complements the Economic Development in Africa Report 2020, to which I also contributed.
    <br/><br/>
    <a href="https://unctad.org/system/files/official-document/aldcafrica2020_en.pdf" rel="noopener">Official report</a><br/>
    <a href="https://unctad.org/osgstatement/economic-development-africa-report-2020-press-conference" target="_blank" rel="noopener">Press release</a> (Summary)<br/>
    <a href="https://unctad.org/system/files/non-official-document/EDAR_2020_background_paper_2_en.pdf" target="_blank" rel="noopener">Mirror trade analysis to detect illicit financial flows</a><br/>
    </p>
    </div>
</div>
<br/>

## Working papers

<b class="pub-title">Does Emission Trading Deliver? Microdata Evidence on Abatement, Trading, and Innovation</b>, with <a href="https://wwz.unibas.ch/de/personen/beat-hintermann/" style="color: inherit; text-decoration: underline;">Beat Hintermann</a>, <a href="https://research-portal.uea.ac.uk/en/persons/corrado-di-maria" style="color: inherit; text-decoration: underline;">Corrado Di Maria</a> and <a href="https://sites.google.com/view/majazarkovic" style="color: inherit; text-decoration: underline;">Maja Žarković</a>. \
<button onclick="togglePanel(this,'abs-4')" class="label panel-btn" aria-controls="abs-4">Abstract</button>
<button onclick="window.open('https://www.dropbox.com/scl/fi/6m3ji1vbpcmjcin5c7fbu/Abatement_Costs_Feb_26.pdf?rlkey=x2tve23ekpaafn16ru24tkwm3&st=6v8pjzeg&dl=0', '_blank')" class="label">URL</button>

<div class="panels">
    <div id="abs-4" class="panel">
    <p>This paper evaluates the empirical performance of emissions trading schemes relative to their theoretical foundations. Leveraging administrative microdata, we estimate the marginal abatement cost (MAC) of carbon dioxide emissions for over 20,000 German manufacturing firms, including roughly 500 entities regulated under the European Union Emissions Trading System (EU ETS). Our analysis uncovers substantial heterogeneity in MACs both within and across industries, highlighting significant potential efficiency gains from reallocating abatement efforts among firms. We find evidence of convergence in MACs among low-cost firms, consistent withactive engagement in abatement. These firms reduced emission intensity primarily by switching to cleaner energy sources and sold more allowances than their high-MAC counterparts, indicating that abating firms capitalize on surplus allowances through trading. These patterns are most pronounced in Phase III of the EU ETS, when carbon prices rebounded. Overall, our findings provide robust evidence that the EU ETS has stimulated abatement, trading, and innovation in ways that align closely with theoretical expectations.</p>
    </div>
</div>


<b class="pub-title">Cost Pass-through, Productivity and Climate Policy in the German Manufacturing Sector</b>, with <a href="https://wwz.unibas.ch/de/personen/beat-hintermann/" style="color: inherit; text-decoration: underline;">Beat Hintermann</a>, <a href="https://research-portal.uea.ac.uk/en/persons/corrado-di-maria" style="color: inherit; text-decoration: underline;">Corrado Di Maria</a>, <a href="https://ulrichwagner.eu/" style="color: inherit; text-decoration: underline;">Ulrich J. Wagner</a> and <a href="https://sites.google.com/view/majazarkovic" style="color: inherit; text-decoration: underline;">Maja Žarković</a>. \
<button onclick="togglePanel(this,'abs-5')" class="label panel-btn" aria-controls="abs-5">Abstract</button>
<button onclick="window.open('https://www.dropbox.com/scl/fi/ozyloicnde0dtmdk75xlv/Cost_pass_through_Feb_26.pdf?rlkey=g13dkgmkq3ywqtr2tvv45rtc4&st=0ne80zhi&dl=0', '_blank')" class="label">URL</button>

<div class="panels">
    <div id="abs-5" class="panel">
    <p>We investigate productivity and cost pass-through among German manufacturing firms using confidential administrative microdata from 2001 to 2019. Our framework allows for the estimation of quantity-based production functions for multi-product firms. Using our parameter estimates, we compute markups and marginal costs, which in turn allow us to measure cost pass-through. We find that firms pass on shocks to materials and energy costs by 83 and 56 cents for a one Euro increase, respectively. Our estimates of cost pass-through do not differ for firms that produce goods deemed to be affected by carbon leakage in the European Union Emissions Trading System (EU ETS), and which as a consequence receive a large share of their emission allowances for free. Furthermore, we find that the incidence of the EU ETS falls largely on consumers, especially in the first two phases. However, we observe an increase in the policy costs borne by firms in the third phase and a resulting decrease in profits.</p>
    </div>
</div>

<b class="pub-title">When Employment Sours, Do Elections Turn Bitter?</b>, single-authored. \
<button onclick="togglePanel(this,'abs-6')" class="label panel-btn" aria-controls="abs-6">Abstract</button>

<div class="panels">
    <div id="abs-6" class="panel">
    <p>The tone of recent U.S. elections has been predominantly negative, raising concerns that politicians' use of personal attacks and aggressive language is fueling anger, threatening the cohesion of society, and inciting violence. This paper investigates the role of economic hardship in driving negative political communication, using the China trade shock as a natural experiment affecting manufacturing unemployment in the United States. Leveraging unstructured data on televised political advertising from 2000 to 2022, I employ language models to recover transcripts and annotate them for the presence, intensity, and aim of attacks on political opponents. Results suggest that local exposure to the China shock amplifies the use of political attacks only in ads favoring challenger candidates. A one-standard-deviation increase in import exposure raises the share of challenger airings containing at least one attack by about two percentage points for three election cycles, from 2008–2010 to 2016–2018. Moreover, the aim of attacks shifts from policy-focused critiques to personal attacks, with language becoming gradually more toxic. These findings suggest that economic hardship slowly steers electoral communication away from policy debate and toward more divisive rhetoric.</p>
    </div>
</div>
<br/>

## Projects and data

<b class="pub-title">Fuzzy Dice Game</b> – Free browser game, try to break it! \
<button onclick="window.open('https://fuzzy-dice-game.onrender.com/', '_blank')" class="label">Play</button>
<button onclick="window.open('https://github.com/leops95/fuzzy-dice-game', '_blank')" class="label">Source code</button>

<b class="pub-title">US State of the State transcripts (1995-2022)</b> \
<button onclick="window.open('https://github.com/leops95/sots', '_blank')" class="label">Dataset</button>


<b class="pub-title">Contributions to the United Nations regular budget (2000-2020)</b> \
<button onclick="window.open('https://leops95.shinyapps.io/unbudget/', '_blank')" class="label">Interactive dashboard</button>
<button onclick="window.open('https://github.com/leops95/unbudget', '_blank')" class="label">Source code and dataset</button>