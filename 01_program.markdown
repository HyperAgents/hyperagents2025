---
layout: page
title: Program
permalink: /program/
---

<style>
table {
    width: 100%;
}
table td:first-child {
    width: 1%;
    white-space: nowrap;
}
</style>

HyperAgents 2025 is held on <strong>October 26, 2025</strong>, at <a href="https://ecai2025.org/venues/" target="_blank">The Engineering School, University of Bologna</a>. The room will be announced once confirmed.

The workshop will be preceded by <a href="https://github.com/w3c-cg/webagents/tree/main/Meetings/2025-10-25-HyperAgents" target="_blank">a hybrid meeting</a> of the <a href="https://www.w3.org/community/webagents/" target="_blank">W3C WebAgents Community Group</a> on the <strong>afternoon of October 25, 2025</strong> — also at the Engineering School (<strong>Room 5.1</strong>).

<table>
    <thead></thead>
    <tr>
        <td>09:00</td>
        <td>Opening and Welcome</td>
    </tr>
    <tr>
        <td>09:15</td>
        <td><a href="#keynote-terry">Keynote: Terry R. Payne (University of Liverpool) — TBA</a></td>
    </tr>
    <tr>
        <td>10:15</td>
        <td>W3C WebAgents CG</td>
    </tr>
    <tr style="background-color: #dddddd">
        <td>10:30</td>
        <td>Coffee Break</td>
    </tr>
    <tr>
        <td>11:00</td>
        <td><a href="#session1">Session 1: Agents in Web Environments</a></td>
    </tr>
    <tr>
        <td>11:45</td>
        <td><a href="#session2">Session 2: Web of Things, Ambient Intelligence, and Industrial Applications</a></td>
    </tr>
    <tr style="background-color: #dddddd">
        <td>12:30</td>
        <td>Lunch</td>
    </tr>
    <tr>
        <td>14:00</td>
        <td><a href="#session3">Session 3: LLM Support and Integration</a></td>
    </tr>
    <tr>
        <td>14:45</td>
        <td><a href="#session4">Session 4: Interaction and Explainability</a></td>
    </tr>
    <tr style="background-color: #dddddd">
        <td>15:30</td>
        <td>Coffee Break</td>
    </tr>
    <tr>
        <td>16:00</td>
        <td><strong>Panel</strong>: Agents, LLMs, and the Web: A Brave New World? <br/><br/>
            <i>Panelists: Stephen Cranefield (University of Otago), Terry R. Payne (University of Liverpool), Ganesh Ramanathan (Siemens), Alessandro Ricci (University of Bologna)</i> <br/><br/> 
            <i>Moderator: Andrei Ciortea (Univesity of St.Gallen)</i></td>
    </tr>
    <tr>
        <td>17:00</td>
        <td>Community Session: The Road Ahead</td>
    </tr>
</table>

<h2>Keynote</h2>

<h3 id="keynote-terry">Terry R. Payne: TBA</h3>

![Terry R. Payne](/assets/terry-payne.webp){: width="200" style="float: left; margin-right: 20px" }

**Bio:** Terry has been conducting research in the area of agent-based computing and knowledge-based systems and services for the last 30 years, and has published more than 195 peer-reviewed papers in the area. His specific interest is in the use of ontological knowledge for the support of agent-based service discovery and provision and is currently exploring the exploration of dialogue-based negotiation approaches to establish contextually-relevant ontological alignment between interacting agents on the fly. This supports the longer term aim of describing, discovering and utilising capability descriptions that agents offer or exploit when collaborating within open and pervasive environments, such as the Internet of Things. He has received numerous research awards, including a Best Industrial Paper award in 2006, and two Distinguished Research paper awards in 2011 & 2012 that recognised his fundamental contribution to his research field his research. He was Program co-chair for the International Semantic Web Conference in 2023, and is a member of SWSA - the Semantic Web Science Association, responsible for promoting and exchanging scholarly work in Semantic Web and related fields throughout the world. He is a Senior Fellow of the Higher Education Authority (SFHEA), and was also awarded a University Learning & Teaching Excellence award in 2013, 2016, 2019 and 2022 for innovative and technology enhanced teaching. His teaching was also recognised by the student body in 2016 when he was awarded the Guild of Students Best Teacher (Faculty of Science) Award.

<h2 id="session1">Session 1: Agents in Web Environments</h2>

<p style="text-align: right;"><a href="#top" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Program</a></p>

<table>
    <thead></thead>
    <tr>
        <td>11:00</td>
        <td><a href="#paper-6">Intelligent Agents: Where Is the Web?</a> (Victor Charpenay)</td>
    </tr>
    <tr>
        <td>11:15</td>
        <td><a href="#paper-1">Affordance Representation and Recognition for Autonomous Agents</a> (Habtom Kahsay Gidey, Alexander Lenz, and Alois Knoll)</td>
    </tr>
    <tr>
        <td>11:30</td>
        <td><a href="#paper-11">The Gap Between BDI Agents and Semantic Hypermedia and What We Can Do About It</a> (Samuele Burattini, Martina Baiardi, Giovanni Ciatto, and Danilo Pianini)</td>
    </tr>
</table>

<h3 id="paper-6">Intelligent Agents: Where Is the Web?</h3>

**Authors:** Victor Charpenay

**Abstract:** This paper reviews agent frameworks and benchmark datasets for software agents evolving in a Web environment. All frameworks and datasets make the assumption that agents interact with their environment through text and images alone, hiding the main abstractions of the Web and its architectural constraints. This study raises the question whether software agents that leverage structured data instead, mostly available in an RDF format, can be more accurate or more computationally efficient than agents based on chatbots.

<p style="text-align: right;"><a href="#session1" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-1">Affordance Representation and Recognition for Autonomous Agents</h3>

**Authors:** Habtom Kahsay Gidey, Alexander Lenz, and Alois Knoll

**Abstract:** The autonomy of software agents is fundamentally dependent on their ability to construct an actionable internal world model from the structured data that defines their digital environment, such as the Document Object Model (DOM) of web pages and the semantic descriptions of web services. However, constructing this world model from raw structured data presents two critical challenges: the verbosity of raw HTML makes it computationally intractable for direct use by foundation models, while the static nature of hardcoded API integrations prevents agents from adapting to evolving services. This paper introduces a pattern language for world modeling from structured data, presenting two complementary architectural patterns. The DOM Transduction Pattern addresses the challenge of web page complexity by distilling a verbose, raw DOM into a compact, task-relevant representation or world model optimized for an agent's reasoning core. Concurrently, the Hypermedia Affordances Representation Pattern enables the agent to dynamically enrich its world model by parsing standardized semantic descriptions to discover and integrate the capabilities of unknown web services at runtime. Together, these patterns provide a robust framework for engineering agents that can efficiently construct and maintain an accurate world model, enabling scalable, adaptive, and interoperable automation across the web and its extended resources.

<p style="text-align: right;"><a href="#session1" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-11">The Gap Between BDI Agents and Semantic Hypermedia and What We Can Do About It</h3>

**Authors:** Samuele Burattini, Martina Baiardi, Giovanni Ciatto, and Danilo Pianini

**Abstract:** Traditional BDI agents, rooted in logic programming, remain challenging to integrate with the hypermedia nature of open Web environments that rely on Semantic Web technologies like RDF and OWL. This paper examines the gap between these paradigms and surveys existing integration efforts on a conceptual and technical level and argues that existing tools offer limited ergonomic support for developers. Our proposal for a deeper integration relies on a generalized BDI engine to enable the development of BDI agents that can directly reason and operate on semantic hypermedia resources. We derive ideal requirements and show an abstract architecture that can be tailored to support different types of beliefs and reasoning mechanisms.

<p style="text-align: right;"><a href="#session1" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h2 id="session2">Session 2: Web of Things, Ambient Intelligence, and Industrial Applications</h2>

<p style="text-align: right;"><a href="#top" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Program</a></p>

<table>
    <thead></thead>
    <tr>
        <td>11:45</td>
        <td><a href="#paper-2">Towards Achieving Adaptive Behaviour of Agents Through Physics-Infused Descriptions of Cyber-physical Devices</a> (Ganesh Ramanathan and Simon Mayer)</td>
    </tr>
    <tr>
        <td>12:00</td>
        <td><a href="#paper-4">Towards Agentic AI support for Hypermedia MAS Models of Smart Environments</a> (Alexandru Sorici, Andrei Olaru, and Adina Magda Florea)</td>
    </tr>
    <tr>
        <td>12:15</td>
        <td><a href="#paper-3">Towards Web-based Autonomous Industrial Systems</a> (Ganesh Ramanathan, Maria Husmann, and Simon Mayer)</td>
    </tr>
</table>

<h3 id="paper-2">Towards Achieving Adaptive Behaviour of Agents Through Physics-Infused Descriptions of Cyber-physical Devices</h3>

**Authors:** Ganesh Ramanathan and Simon Mayer

**Abstract:** Cyber-physical devices (CPDs) are now widely employed in environments like smart buildings and factories. Many of these devices are involved in managing physical processes, such as the transformation of substances and energy. When it comes to achieving adaptive behavior through autonomous artificial agents that use such CPDs as artifacts in the pursuit of their goals, understanding (by the agent) both the technical interface of a CPD and its underlying physical processes becomes important. The W3C Web of Things Thing Description (TD) standard aims to address this challenge; however, hitherto, only the possibility of achieving technical interoperability has been explored, while the inclusion of the semantics of underlying physical processes remains to be explored. In this article, we describe our work in progress, which seeks to demonstrate how existing models that enable the description of physical processes can be used to embed such knowledge directly in the TDs. We further explore how this may enable artificial agents in a hypermedia environment to discover and utilize distributed CPDs without relying on a centralized, authoritative source of knowledge. We present intermediate results from our evaluation of an intelligent room automation system that demonstrates adaptive behavior through runtime discovery of CPD affordances.

<p style="text-align: right;"><a href="#session2" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-4">Towards Agentic AI support for Hypermedia MAS Models of Smart Environments</h3>

**Authors:** Alexandru Sorici, Andrei Olaru, and Adina Magda Florea

**Abstract:** Goal-driven interaction in Smart Environments brings significant challenges due to the variety of devices, the heterogeneity or lack of formal specifications for affordances, and the complexity of planning. Recent advances in hypermedia-based MAS and reasoning-capable foundational machine learning models are making goal-driven interaction frameworks realistically plausible. We demonstrate a prototype framework for the management of goal-driven smart environment interactions that builds upon: (i) Hypermedia MAS environment modeling, (ii) resource signification to capture usage experience, (iii) LLM support for agent reasoning, and (iv) the formation of communities in which agents can leverage the experience of peers to better achieve their own goals. We showcase framework functionality in a smart office simulated scenario.

<p style="text-align: right;"><a href="#session2" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-3">Towards Web-based Autonomous Industrial Systems</h3>

**Authors:** Ganesh Ramanathan, Maria Husmann, and Simon Mayer

**Abstract:** Industrial infrastructures employ control systems to manage their complex electro-mechanical installations in a safe and energy-efficient way. Semantic Web technologies have been utilized to create machine-understandable descriptions of requirements, technical design, and fundamental domain knowledge, yielding promising results in enabling the automated engineering of controls and, more broadly, in the development of autonomous systems. Concurrently, industrial automation systems are increasingly adopting the Web architecture. In this article, we first report on our experience gathered over the past decade at Siemens AG in bringing the fragmented Semantic Web-based ontologies in engineering towards creating holistic system knowledge of smart infrastructures. Then, based on our practical experience, we share that the role of Semantic Web technologies goes beyond enabling automated engineering and highlight its potential to create knowledge-infused web-based autonomous systems. However, we note that the potential is currently under-exploited in the context of evolution in industrial automation systems, where classical closed architectures are giving way to large-scale web-based deployments. We then describe our ongoing research to address this dissonance by adopting hypermedia multi-agent systems as an architectural paradigm in industrial automation.

<p style="text-align: right;"><a href="#session2" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h2 id="session3">Session 3: LLM Support and Integration</h2>

<p style="text-align: right;"><a href="#top" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Program</a></p>

<table>
    <thead></thead>
    <tr>
        <td>14:00</td>
        <td><a href="#paper-8">A Vision for LLM-based Interaction Assistance for Autonomous Agents on the Semantic Web</a> (Danai Vachtsevanou, Jérémy Lemée, Valentina Tamma, Terry R. Payne, Andrei Ciortea, and Simon Mayer)</td>
    </tr>
    <tr>
        <td>14:15</td>
        <td><a href="#paper-9">Are LLMs and the Model Context Protocol Sufficient for Automating Web-Based Information Processing?</a> (Stephen Cranefield)</td>
    </tr>
    <tr>
        <td>14:30</td>
        <td><a href="#paper-12">Converging Hypermedia, Protocols, and Knowledge Architectures: A New Paradigm for Grounded and Interoperable LLM-Agent Systems</a> (Maksim Ilin)</td>
    </tr>
</table>

<h3 id="paper-8">A Vision for LLM-based Interaction Assistance for Autonomous Agents on the Semantic Web</h3>

**Authors:** Danai Vachtsevanou, Jérémy Lemée, Valentina Tamma, Terry R. Payne, Andrei Ciortea, and Simon Mayer

**Abstract:** Advances in the Semantic Web and the Web of Things have enabled the dynamic advertisement of interaction descriptions, which allow autonomous agents to discover and reason about actions in hypermedia environments. However, these descriptions occasionally fall short in open, dynamic settings—for example, they may contain incomplete knowledge about unexpected situations, or information that does not directly address the needs of heterogeneous agents. In practice, such gaps are typically bridged by humans, often relying on their common sense. In this paper, we envision the integration of Large Language Models (LLMs) into Hypermedia Multi-Agent Systems (MAS) to leverage their world knowledge to fill information gaps at run time and enable scalable support for agent interaction in open and dynamic hypermedia environments. Our proposal lays the groundwork for a framework that considers LLM-based assistive functions for interaction in Hypermedia MAS, enabling the parameterisation and contextual grounding of interaction, methods for agents to leverage this assistance, and safeguards to ensure integrity and transparency. With these ideas, our aim is to inspire further research exploring the extent to which LLMs can assist in managing semantic descriptions in hypermedia environments at run time, while balancing scalable interaction assistance with identified challenges.

<p style="text-align: right;"><a href="#session3" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-9">Are LLMs and the Model Context Protocol Sufficient for Automating Web-Based Information Processing?</h3>

**Authors:** Stephen Cranefield

**Abstract:** More than two decades ago, the concept of the Semantic Web was motivated by a vision of personal assistant agents that fulfil users' goals by locating, accessing and reasoning about information and services on the web. Until the recent advent of agents that can act on instructions generated by large language models (LLMs), progress towards this vision has been slow. Now, the natural language understanding abilities of LLMs and their emerging ability to generate and follow instructions suggest that LLM-powered agents may provide a path towards developing such general-purpose assistant agents. This paper presents a case study of automating a multi-step web-based information seeking and filtering task using a large language model provided with tool access via the Model Context Protocol (MCP) and information about relevant web resources. We found this was possible, but only by providing the LLM with detailed information about how to use the resources. We discuss the reasons for this and how this requirement could be eliminated by providing discovery mechanisms and web page usage information intended for LLMs. We also propose the development of higher-level models of web resources in terms of information processing goals or tasks.

<p style="text-align: right;"><a href="#session3" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-12">Converging Hypermedia, Protocols, and Knowledge Architectures: A New Paradigm for Grounded and Interoperable LLM-Agent Systems</h3>

**Authors:** Maksim Ilin

**Abstract:** The evolution of LLM-powered agents has led to a distinction between single-purpose AI Agents and collaborative Agentic AI systems. While powerful, both face persistent challenges in grounding, interoperability, and governance when operating in open Web environments. This paper argues that a new, more robust paradigm is emerging from a deep convergence of architectural principles and modern standards. We posit that Hypermedia Multi-Agent Systems (HMAS) provide the foundational philosophy for Web-native agency, where the concepts of W3C Web of Things (WoT) "Things" and Model Context Protocol (MCP) "Tools" are unified as complementary specializations of hypermedia-described Web resources with discoverable affordances. This unified view enables the design of advanced Agentic AI systems—composed of autonomous AI Agents grounded in foundational definitions of agency—that can reliably perceive and act upon a rich environmental fabric of physical (WoT) and semantic (DKG) resources. By analyzing this convergence and presenting an illustrative agentic architecture, we demonstrate how this paradigm offers enhanced grounding, true interoperability, and clearer pathways to trustworthy governance, providing a structured approach for developing the next generation of scalable and context-aware autonomous systems.

<p style="text-align: right;"><a href="#session3" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h2 id="session4">Session 4: Interaction and Explainability</h2>

<p style="text-align: right;"><a href="#top" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Program</a></p>

<table>
    <thead></thead>
    <tr>
        <td>14:45</td>
        <td><a href="#paper-5">CoCoMaMa: Contextual Combinatorial Multi-Armed Bandit Router for Multi-Agent Systems with Volatile Arms</a> (Jonathan Rau, Jonathan Bader, Philipp Wiesner, and Odej Kao)</td>
    </tr>
    <tr>
        <td>15:00</td>
        <td><a href="#paper-10">A Vision on Algebraic Flows for Declarative Resource Descriptions</a> (Jitse De Smet, Ruben Verborgh, and Ruben Taelman)</td>
    </tr>
    <tr>
        <td>15:15</td>
        <td><a href="#paper-7">Towards an Ontology for Uniform Representations of Agent State for Heterogeneous Inter-Agent Explanations</a> (Katharine Beaumont, Elena Yan, and Rem Collier)</td>
    </tr>
</table>

<h3 id="paper-5">CoCoMaMa: Contextual Combinatorial Multi-Armed Bandit Router for Multi-Agent Systems with Volatile Arms</h3>

**Authors:** Jonathan Rau, Jonathan Bader, Philipp Wiesner, and Odej Kao

**Abstract:** Agentic Large Language Models (LLMs) are designed for specialized objectives using fine-tuning, prompting techniques, and tool calling to outperform general-purpose models in their expert domains. Standardization efforts like the Agent2Agent Protocol could drastically increase the number and heterogeneity of experts available via the Web. A router is required to find the best agent for any given task. However, existing LLM routing methods use a fixed-sized pool of models and often rely on offline training data such as benchmarks. We propose CoCoMaMa and Neural-CoCoMaMa, a combinatorial contextual volatile multi-armed bandit approach that leverages similarities between tasks and agents by learning on online feedback. It can handle volatile arms by incorporating agent cards as defined by the Agent2Agent Protocol without requiring changes to the internal structures or retraining. Our experimental evaluation shows that CoCoMaMa and Neural-CoCoMaMa achieve better results than respective state-of-the-art algorithms using the LLM routing dataset SPROUT and a novel extended version of SPROUT with synthetic specialized agents.

<p style="text-align: right;"><a href="#session4" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-10">A Vision on Algebraic Flows for Declarative Resource Descriptions</h3>

**Authors:** Jitse De Smet, Ruben Verborgh, and Ruben Taelman

**Abstract:** In the age of agentic systems, correct autonomous data management is increasingly critical. Agents need to discover what resources exist and how to interact with them, but existing interface description frameworks that could provide such support either leave too much open to interpretation or fail to model underlying resources, which are not directly exposed. To address this gap, we propose a declarative description that describes underlying resources and their transformations by modeling interfaces as algebraic flows that declaratively define how underlying resources are exposed, derived, and manipulated. We detail our vision by walking through an example use case that showcases the various problems agents have when interacting with data interfaces and incrementally present our solution of modeling how data flows within the system. Our approach shows that interface developers can express their systems using familiar query languages, while enabling autonomous agents to reason about the consequences of actions and determine required operations to manipulate resources safely and predictably. This makes deterministic interactions with complex, asymmetric information interfaces possible. Looking ahead, we aim to formalize this approach into a theoretically sound framework with a proof-of-concept implementation. Additionally, we identify promising avenues for integrating policy-aware semantics and privacy-preserving interface disclosure.

<p style="text-align: right;"><a href="#session4" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>


<h3 id="paper-7">Towards an Ontology for Uniform Representations of Agent State for Heterogeneous Inter-Agent Explanations</h3>

**Authors:** Katharine Beaumont, Elena Yan, and Rem Collier

**Abstract:** Inter-agent explanations are an emerging approach to agent communication that enable agents to share their cognitive processes in order to reach mutual understanding. A key challenge is that agents are often heterogeneous, built on different paradigms and architectures, which makes their internal representations difficult to exchange directly. The Semantic Web offers key technologies, in the form of ontologies, that can facilitate interoperability and shared understanding between hypermedia agents operating on the Web. We present work towards providing Agent Abstraction ontologies that would allow hypermedia agents to abstract and exchange information about their cognitive processes as part of inter-agent explanations.

<p style="text-align: right;"><a href="#session4" style="padding: 5px 10px; background-color: #8BC34A; color: white; text-decoration: none; border-radius: 3px;">↑ Back to Session</a></p>
