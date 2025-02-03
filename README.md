# smartagents-workshop
Repository for the Web pages for the upcoming Smart Agents Workshop, e.g., the Call-for-Participation

## General background
* Thanks to the advancement of HTML5 and related Web technologies, Web applications with speech capability is getting more and more popular for ease of user-interaction and richer user experience such as Apple's SIRI, Google's Voice Assistant and Amazon's Alexa.
* Thus voice agents are one of the essential applications on various devices especially mobile phones, tablet devices, eBook readers, and gaming platforms. In addition, traditional platforms such as TV's, audio systems and automobiles are rapidly becoming capable of speech interaction.
* Also these days smart speakers are getting a portal for IoT services including smart homes.
* Dduring [one of the breakout sessions at TPAC 2019 in Fukuoka](https://www.w3.org/2019/09/18-voice-minutes.html), there was discussion about potential needs for improved voice agents for web services.
* This resulted in creation of [Issue 221 Proposal: Workshop on User-friendly Smart Agents on the Web - Voice interaction and what's next?](https://github.com/w3c/strategy/issues/221)
 
## Focus
* See the current status of the voice-enabled smart platforms integrating multi-vendor services/applications/devices:
    * Interaction with smart devices also in the Web of Things
    * Control from Web browsers
    * Interoperability and access to controls for accessibility/usability, e.g., smart navigation
* and discuss what is missing for the voice interaction technology to be deployed globally for all the languages throughout the world

 
## Possible topics
* Clarification of use cases and their requirements
* Summary of the current status:   
    * Overview of existing browser support/platforms
    * What we already have in the browsers/platforms
    * Common issues on the interoperability among the browsers/platforms
    * Missing features with the existing APIs
* Needs of the users and the developers:
    * Smarter interaction with LLMs for easier use, e.g.: 
        * Hallucinations: LLMs can sometimes generate outputs that sound plausible but are factually incorrect.
        * Ambiguity in Outputs: Inconsistent or vague responses can lead to confusion in automated workflows.
        * Lack of Accountability: When errors occur, tracing the root cause in an LLM’s predictions can be difficult.
    * Improved pronunciation for speech synthesis in various languages. See also the [APA WG's video for TPAC 2020](https://www.w3.org/2020/10/TPAC/apa-pronunciation.html).
    * Applying the advanced voice technology for Web services (Speech style, Expression, Feeling, Emotion, etc.)
    * Dealing with both the input entities (sensors/applications) and output entities (actuators/devices/digital twins) from various vendors and coordination thereof
    * Presentation issues such as how/what/when to transfer necessary information from the input entities (possibly the users, devices or applications) and present it to the output entities (also possibly the users, devices or applications)
    * Integration of multiple interchangeable modalities (typing, handwriting, voice, etc.)
* Underlying technologies:
    * Smarter integration of multiple applications, e.g. via Agentic AI
    * Applications/services/devices from different multiple vendors
    * Unified data format and protocols for data transfer
    * State transition management model and service lifecycle
    * Natural language processing technology and resources for that, e.g., phonetic databases, parallel corpora
    * Possible improved model and architecture for voice interaction and expected technologies (also the relationship between those technologies and the Web technology)
* Horizontal platform:
    * Discovery of resources
    * Privacy and security
    * Accessibility and usability
    * Internationalization and compatibility with region-specific technology
 
## Example of related use cases
The related technology area is broad including:
 
* Voice agent
* Connected car
* Smart homes/Smart factories/Smart cities
* Smart speakers/Smartphones as a portal/user device
* IoT services in general

For example, Hybrid TV services (Web+TV integration based on HTML5, Second Screen, TTML, etc.) and smart home devices and services. Possibly additional proprietary technology like MiniApps, e.g.:

* Asking the voice agent "I want to order takeaway." on the TV in the living room to order a pizza.
* Choosing the food using voice commands and saying "checkout" to the smart watch would process the payment.

Another example is in searching for television content. The user asks "Play [name of an episodic TV show]" and the voice assistant will speak "Here's what I found" while displaying search results on the TV. A useful user requirement may be the ability to request congruent user feedback (ie if voice is used for input then speech is used for feedback).

> **NOTE:**  The above is just a few example of the possible use cases, and your own use cases are welcome and really appreciated :)

## Who to attend?
* Many possible stakeholders including:
    * Service providers/System implementers
    * Govt (like Singapore)
    * Users from various countries/communities
* Liaisons
    * CHIP (Amazon, Apple, Google and Zigbee)
    * OCF
    * oneM2M
    * Singapore Govtech

<!--
See also the [rendered HTML](https://w3c.github.io/smartagents-workshop/)
-->
