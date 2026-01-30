# Scientific Literature Review: Emotion-Aware Smart Fashion

## Executive Summary

Emotion-aware smart fashion represents an emerging interdisciplinary field that integrates wearable technology, affective computing, and fashion design to create garments and accessories capable of detecting, responding to, and communicating human emotional states. This literature review synthesizes findings from 30 peer-reviewed publications spanning 2004 to 2025, examining the intersection of emotional states, wearable technology, and fashion design. The field has evolved from early conceptual explorations to sophisticated systems employing physiological sensors, machine learning algorithms, and adaptive materials. Key applications include mental health support, interpersonal communication enhancement, emotion regulation, and self-expression. Current systems achieve emotion recognition accuracies exceeding 97%, utilizing diverse sensing modalities including facial expression analysis, physiological signals (heart rate, skin conductance, temperature), and movement patterns. The review identifies three primary technological approaches: physiological sensing systems, facial expression recognition platforms, and interactive textile interfaces. Despite significant advances, challenges remain in seamless fashion integration, user acceptance, privacy concerns, and long-term wearability. Future directions point toward sustainable neurofashion frameworks, edge-AI processing for privacy preservation, and more sophisticated emotion regulation mechanisms.

## Table of Contents

1. [Introduction](#1-introduction)
2. [Background and Theoretical Foundations](#2-background-and-theoretical-foundations)
3. [Emotion Detection Technologies and Methods](#3-emotion-detection-technologies-and-methods)
   - 3.1 [Physiological Signal-Based Approaches](#31-physiological-signal-based-approaches)
   - 3.2 [Facial Expression Recognition Systems](#32-facial-expression-recognition-systems)
   - 3.3 [Movement and Gesture-Based Detection](#33-movement-and-gesture-based-detection)
4. [Wearable Integration and Fashion Design](#4-wearable-integration-and-fashion-design)
   - 4.1 [Smart Textiles and Materials](#41-smart-textiles-and-materials)
   - 4.2 [Actuators and Output Modalities](#42-actuators-and-output-modalities)
   - 4.3 [Design Aesthetics and User Acceptance](#43-design-aesthetics-and-user-acceptance)
5. [Application Domains and Use Cases](#5-application-domains-and-use-cases)
   - 5.1 [Mental Health and Emotion Regulation](#51-mental-health-and-emotion-regulation)
   - 5.2 [Interpersonal Communication](#52-interpersonal-communication)
   - 5.3 [Self-Expression and Social Interaction](#53-self-expression-and-social-interaction)
6. [Key Findings and Comparative Analysis](#6-key-findings-and-comparative-analysis)
7. [Discussion](#7-discussion)
   - 7.1 [Technical Achievements and Limitations](#71-technical-achievements-and-limitations)
   - 7.2 [Design and User Experience Challenges](#72-design-and-user-experience-challenges)
   - 7.3 [Ethical and Privacy Considerations](#73-ethical-and-privacy-considerations)
8. [Future Directions and Recommendations](#8-future-directions-and-recommendations)
9. [Conclusion](#9-conclusion)
10. [References](#10-references)

## 1. Introduction

The convergence of affective computing, wearable technology, and fashion design has given rise to emotion-aware smart fashion—garments and accessories that can sense, interpret, and respond to human emotional states. This emerging field addresses fundamental human needs for emotional expression, regulation, and communication while challenging traditional boundaries between technology and clothing. As wearable computing has predominantly focused on accessories such as smartwatches and fitness trackers, the actual garments people wear have remained largely untouched by the digital revolution [28]. Emotion-aware smart fashion seeks to bridge this gap by seamlessly integrating computational capabilities directly into clothing and fashion accessories.

The motivation for emotion-aware smart fashion stems from multiple domains. Mental health concerns affect over 280 million people worldwide, with anxiety disorders being among the most prevalent conditions [21]. Traditional emotion management methods often rely on subjective techniques and personal willpower, which can prove inadequate in high-stress situations [25]. Simultaneously, the increasing digitization of human interaction has created new challenges for emotional communication, particularly in contexts where facial expressions are obscured or where individuals struggle to express their feelings [5], [12].

This literature review examines the state of the art in emotion-aware smart fashion, synthesizing findings from 30 peer-reviewed publications published between 2004 and 2025. The review addresses three core research questions: (1) What technologies and methods are employed for emotion detection in wearable fashion contexts? (2) How are these technologies integrated into fashion design while maintaining aesthetic appeal and wearability? (3) What are the primary application domains, demonstrated outcomes, and remaining challenges in this field?

## 2. Background and Theoretical Foundations

The theoretical foundations of emotion-aware smart fashion draw from multiple disciplines, including affective computing, fashion theory, human-computer interaction, and cognitive psychology. Affective computing, pioneered in the 1990s, focuses on developing systems that can recognize, interpret, and simulate human emotions. When applied to fashion, this creates what has been termed "The Emotional Wardrobe"—clothing that can both represent and stimulate emotional responses through technological interfaces [14], [24].

Textiles have historically served as important carriers for emotional expression, with fashion providing a means for individuals to communicate identity, mood, and social status [2]. The integration of wearable technology brings computational power closer to the body, enabling new forms of emotional expression and regulation [2], [7]. This merger creates opportunities for what Stead describes as "a more personal and provocative definition of self, one which actively involves the wearer in a mutable aesthetic identity" [24].

Several theoretical frameworks guide the design of emotion-aware fashion systems. Kansei engineering, a method that translates emotional responses into design parameters, has been employed to evaluate the affective impact of interactive clothing [16], [17], [18]. The concept of "wearing embodied emotions" positions wearable technology as a living surface that converts intangible emotional data into tangible, communicative forms [7], [13]. More recently, the "Sixth Sense Garment" framework has integrated affective computing with neuroaesthetics and circular economy theory, proposing sustainable approaches to emotion-aware fashion [6].

The evolution of smart clothing has been conceptualized in stages, with emotion-aware systems representing advanced iterations. Wang et al. propose a "smart clothing 3.0" evolutionary roadmap and an "Internet of Clothes" (IoC) concept, where garments form interconnected networks capable of sensing and responding to emotional states [16], [17]. This progression reflects a shift from purely functional wearables to systems that synchronize technical functionality with human emotional expression.

## 3. Emotion Detection Technologies and Methods

### 3.1 Physiological Signal-Based Approaches

Physiological signal monitoring represents the most prevalent approach for emotion detection in smart fashion systems. These methods leverage the autonomic nervous system's responses to emotional stimuli, which manifest as measurable changes in bodily functions. The most commonly employed physiological signals include heart rate (HR), skin conductance/galvanic skin response (GSR), body temperature, and perspiration [1], [11], [12].

Qishu's nanofibre-based intelligent emotion-aware clothing system exemplifies a comprehensive physiological approach, collecting pulse, body temperature, and perspiration data through embedded sensors [1]. The system employs a self-sufficient weight-tuned Kohonen neural network (SW-KNN) for emotion classification, with white shark optimization (WSO) enhancing accuracy. Preprocessing involves min-max normalization, and Fast Fourier Transform (FFT) extracts relevant features from the raw physiological data. This approach achieved remarkable performance metrics, with 97.8% accuracy and 98.1% precision in emotion classification [1].

The Smart Scarf project demonstrates a more accessible implementation, utilizing a MAX30100 pulse oximeter for heart rate monitoring and an HiLetgo GY-906 MLX90614ESF sensor for skin temperature measurement [12]. An Arduino microcontroller processes these signals to classify emotions into four categories: neutral, happy, sad, and angry. The system provides visual feedback through a WS2812B LED light strip that changes color based on detected emotional states, with Bluetooth connectivity enabling mobile application integration [12].

Xia et al. explored multiple physiological modalities, including electrocardiogram (ECG), blood volume pulse (BVP), and respiration (RSP) signals [11]. Their approach employed Support Vector Machines (SVM) and Binary Tree Methods for emotion classification, demonstrating the applicability of diverse machine learning algorithms to physiological emotion recognition. The integration of these sensors into clothing required careful consideration of waterproofing and thermal insulation properties [11].

The SWARM project utilized biosensors for heart rate and perspiration monitoring, with algorithms determining affective baselines and detecting changes [9]. This system's modular soft circuitry design, which fuses conductive fabric with actuation components, represents an innovative approach to seamless sensor integration. User studies revealed preferences for specific feedback modalities, with heat and music identified as effective mood-changers and vibrations preferred for alerts [9].

### 3.2 Facial Expression Recognition Systems

Facial expression analysis offers an alternative approach to emotion detection, leveraging computer vision and machine learning to interpret emotional states from facial features. This method aligns with natural human communication patterns, as facial expressions constitute a primary channel for emotional expression [29].

The emotion-reacting wear developed by Kai et al. and ISHIUCHI et al. employs digital cameras integrated into transparent polycarbonate collars to capture facial images [3], [4]. The system utilizes Microsoft Azure Cognitive Services Face API to generate an 8-dimensional facial expression vector, enabling real-time emotion estimation. The design incorporates a "retro-futurism" aesthetic concept, demonstrating that functional emotion detection can be integrated with fashion-forward design principles [3], [4].

Evaluation of the facial expression recognition system revealed varying accuracy across emotion categories. While happiness was correctly identified with high reliability, other emotions exhibited lower recognition rates, with many expressions misidentified as neutral [4]. This finding highlights a common challenge in facial expression recognition: the difficulty of distinguishing subtle emotional states and the prevalence of neutral expressions in everyday contexts.

Emolleia, a wearable kinetic flower display, employs facial tracking technology with an integrated camera to detect and categorize facial expressions into five categories: happy, sad, surprise, neutral, and disgust [15]. The system translates detected emotions into kinetic animations performed by 3D-printed flowers made from Elastic 50A resin, connected to servo motors via strings. An emotion elicitation study with 50 participants demonstrated that different animated motions produced significantly different perceived valence and arousal levels, validating the system's effectiveness in communicating emotional states [15].

An alternative approach to facial expression detection employs electromyography (EMG) of facial muscles rather than visual analysis. Ishiuchi et al.'s smart fashion accessory uses EMG to identify positive facial expressions even when obscured by face masks [5]. This method addresses a specific contemporary challenge—the communication interference caused by facial coverings—by detecting muscle activity associated with expressions like "active," "enthusiastic," and "excited" [5].

### 3.3 Movement and Gesture-Based Detection

Movement-based approaches to emotion detection leverage the relationship between bodily motion and emotional states. This method recognizes that emotions manifest not only in facial expressions and physiological changes but also in movement patterns, gestures, and body language [2].

Jiang's work on movement-based interactive textiles explores how wearable technology can infer affect from movement patterns [2]. By embedding motion sensors into textile structures, the system can detect changes in the wearer's physical activity and posture, which correlate with emotional states. This approach enables the garment itself to serve as both sensor and interface, creating a more integrated emotion-aware system [2].

The integration of movement detection with other sensing modalities creates multimodal emotion recognition systems. Jiang et al.'s smart interactive shawl combines electrodermal activity (EDA) sensors with pressure-based sensors to detect both physiological arousal and movement-based interactions [27]. Users can interact with the shawl through movement, visualizing their emotional state and actively engaging in emotion regulation [27].

## 4. Wearable Integration and Fashion Design

### 4.1 Smart Textiles and Materials

The integration of emotion detection and response capabilities into wearable fashion requires careful consideration of materials, construction techniques, and textile properties. Smart textiles serve as the foundation for emotion-aware fashion, enabling the seamless incorporation of electronic components while maintaining comfort, flexibility, and aesthetic appeal.

Nanofibre technology represents a cutting-edge approach to smart textile development. Qishu's system utilizes nanofibre-based fabrics that can embed sensors and actuators while maintaining textile-like properties [1]. The nanofibre structure provides high surface area for sensor integration and enables the garment to continuously modify its features based on detected emotional states [1].

Conductive fabrics play a crucial role in creating flexible circuitry within garments. The SWARM project demonstrates the use of conductive fabric fused with actuation components to create modular soft circuits [9]. This approach employs Z-Tape as a conductive adhesive, enabling the creation of flexible electronic pathways within cotton canvas and knit fabrics. The modular hexagon-shaped design allows for interchangeable components, facilitating customization and repair [9].

Material selection for interactive parent-child clothing demonstrates the diversity of smart textile approaches. Wang et al. employed DuPont Tyvek paper fabric for its durability and visual effects, 3M luminous reflective fabric for enhanced visibility, and TPU transparent film for weather resistance [17]. These materials were selected not only for their functional properties but also for their contribution to the garment's aesthetic and emotional impact [17].

The integration of electronic components into textiles requires consideration of practical concerns such as waterproofing, thermal insulation, and washability. Xia et al. addressed these challenges in their interactive fashion designs, ensuring that embedded sensors and LEDs could withstand the demands of daily wear [11]. The "Breathing Dress" and "Heartthrob Dress" prototypes demonstrated structurally innovative approaches to housing electronic components while maintaining fashion-forward aesthetics [11].

### 4.2 Actuators and Output Modalities

Emotion-aware fashion systems employ diverse output modalities to communicate detected emotional states or provide feedback for emotion regulation. These actuators transform digital information into physical, perceptible changes in the garment's appearance or behavior.

Visual feedback through light-emitting diodes (LEDs) represents the most common output modality. The Smart Scarf employs a WS2812B LED light strip that changes color based on detected emotions, with different colors mapped to specific emotional states [12]. The emotion-reacting wear developed by ISHIUCHI et al. uses RGB-LEDs with colors mapped to Plutchik's wheel of emotion, creating a theoretically grounded visual representation of emotional states [4]. The gradual illumination of LEDs in response to proximity, as demonstrated in interactive clothing for couples, creates subtle yet meaningful emotional communication [18].

Kinetic actuation provides a dynamic, three-dimensional form of emotional expression. Emolleia's 3D-printed flowers, controlled by servo motors, perform eight pre-defined animations corresponding to different emotional states [15]. The BioWear project explores kinetic accessories that manipulate their appearance based on the wearer's body metrics, creating visible manifestations of inner emotional states [8]. These kinetic elements add a performative dimension to emotion-aware fashion, making emotional states visible through movement.

Haptic feedback through vibration and temperature modulation offers more private, personal forms of emotional communication. The SWARM system incorporates heat, vibration, audio, and lighting as actuation modalities [9]. User studies revealed that heat and music were preferred for mood modification, while vibrations were favored for alerts. This finding suggests that different output modalities serve distinct functions in emotion-aware systems—some for private awareness and regulation, others for interpersonal communication [9].

Audio feedback represents another dimension of emotional expression in smart fashion. The emotion-reacting wear employs a rule-based search phrase generator to select music for Bluetooth neck speakers based on detected emotions [4]. This approach leverages music's well-established capacity to influence mood and emotional states, creating an auditory complement to visual and haptic feedback.

Thermochromic and shape-changing materials offer emerging possibilities for emotion-aware fashion. Farahi's work explores color- and shape-changing operations as interactive design tools that can physically adapt to user emotional states [10]. These material interfaces create an affective feedback loop where the garment's physical properties reconfigure based on detected emotions, potentially influencing the wearer's emotional state and social interactions [10].

### 4.3 Design Aesthetics and User Acceptance

The success of emotion-aware fashion depends not only on technical functionality but also on aesthetic appeal and user acceptance. Several studies have explicitly addressed the challenge of creating systems that users would willingly wear in daily life.

The "retro-futurism" design concept employed in emotion-reacting wear demonstrates one approach to aesthetic integration [3], [4]. This design philosophy combines vintage fashion elements (glen-check fabric, synthetic leather) with futuristic technological components (transparent polycarbonate collars, integrated cameras), creating a distinctive aesthetic that celebrates rather than conceals the technological integration [4].

User-centered design processes have proven essential for creating acceptable emotion-aware fashion. The Smart Scarf project employed iterative design with user feedback, focusing on comfort and wearability [12]. Evaluation with 10 participants revealed that the scarf provided comfort, enhanced social engagement, and assisted in tracking and controlling emotions. Importantly, users found the design aesthetically acceptable for daily wear [12].

The SWARM project's scarf form-factor with interchangeable hexagonal modules addresses both aesthetic and functional concerns [9]. The modular design allows users to customize the appearance and functionality of their garment, accommodating diverse aesthetic preferences while enabling repair and upgrades. The use of cotton canvas and knit fabrics ensures that the technological components are integrated into a familiar, comfortable textile format [9].

Evaluation studies have employed Kansei engineering methods to assess the emotional impact of interactive clothing designs. Wang et al.'s studies of interactive clothing for couples demonstrated that the interactive versions elicited significantly higher emotional responses than non-interactive controls [16], [18]. The interactive clothing correlated well with emotional expressive patterns, with LEDs illuminating gradually as wearers' distance decreased, reaching full brightness below one meter [18].

The challenge of balancing technological functionality with humanistic emotion remains a key concern. Wang et al. noted that technology-oriented clothing can lack humanistic emotion, identifying emotional value enhancement as a crucial future research direction [17]. This observation underscores the importance of design approaches that prioritize emotional resonance alongside technical capability.

## 5. Application Domains and Use Cases

### 5.1 Mental Health and Emotion Regulation

Mental health support and emotion regulation represent primary application domains for emotion-aware smart fashion. These systems aim to help individuals monitor, understand, and manage their emotional states, potentially preventing the progression of mental health disorders.

The emotion-reacting fashion system developed by ISHIUCHI et al. explicitly targets mental health support, aiming to monitor internal psychological and emotional states to prevent the unconscious progression of mental disorders [4]. The system provides visual and audio feedback reflecting detected emotions, with the potential to suppress negative emotional states and enhance mental well-being [4].

SCAARF (Subtle Conditioning Approach for Anxiety Relief Facilitation) demonstrates a therapeutic application of emotion-aware fashion [21]. The smart scarf delivers subliminal anxiety relief interventions through a wearable device paired with a mobile application. A three-week evaluation with anxiety-suffering users revealed that the system effectively helped users relax and cope with anxious states of mind [21]. This approach differs from conventional mental health technologies by offering a more subtle, less obtrusive intervention method [21].

Dejene's critical review of wearable smart textiles for mood regulation highlights the potential of these technologies for stress reduction, anxiety management, and emotional resilience [25]. The review emphasizes that effective mood regulation is essential for maintaining psychological well-being, particularly during critical developmental phases such as adolescence. Smart textiles equipped with sensors and actuators can provide continuous, objective mood monitoring and regulation, addressing limitations of traditional methods that rely on personal willpower and subjective techniques [25].

The smart interactive shawl developed by Jiang et al. demonstrates practical emotion regulation capabilities [27]. The system helps users visualize their emotions through biofeedback and reduce stress levels through movement-based interaction. User studies confirmed that the shawl could effectively help users understand their emotional state and adjust it when necessary [27].

The "Sixth Sense Garment" framework proposes emotion-aware fashion as a tool for stress reduction and wearer regulation [6]. By dynamically adapting appearance and tactility based on biometric and environmental signals, the system aims to promote emotional well-being while also extending product lifetimes through sustainable design principles [6].

### 5.2 Interpersonal Communication

Emotion-aware fashion serves as a medium for enhanced interpersonal communication, making internal emotional states visible to others and facilitating deeper, more authentic human connections.

Interactive clothing for couples exemplifies this application domain. Wang et al.'s prototypes use proximity sensors and LEDs to reflect the emotional relationship between wearers [16], [18]. As the distance between partners decreases, the LEDs illuminate gradually, reaching full brightness when they are within one meter of each other. This creates a subtle yet meaningful form of emotional communication that enhances the couple's awareness of their physical and emotional proximity [18].

The BioWear project explores using wearable technology to create deeper, more authentic human communication [8]. By sensing and displaying emotions through kinetic accessories that manipulate their appearance based on body metrics, the system reveals the wearer's inner, genuine emotional state. This raises important questions about communication boundaries and the extent to which technology should make private emotional states publicly visible [8].

Ugur's work on wearing embodied emotions positions wearable technology as a living surface that converts intangible emotional data into tangible forms for enhanced human-to-human interaction [7]. The research explores how technology can dissolve in use, becoming a natural extension of the body that facilitates rather than mediates emotional communication [7].

The smart fashion accessory designed to communicate positive facial expressions hidden by face masks addresses a specific communication challenge [5]. By using EMG to detect positive expressions and translating them into RGB LED patterns in earrings, the system enables emotional communication even when facial features are obscured. Evaluation confirmed that the accessory successfully transmitted "active," "enthusiastic," and "excited" expressions, facilitating smoother social interactions [5].

Interactive parent-child clothing demonstrates emotion-aware fashion's potential for strengthening family bonds [17]. The system creates a micro-cyber world that fosters emotional connection through IoT-enabled visual effects that respond to proximity. This application emphasizes emotional design and cultural awareness, aiming to enhance family belonging and interaction in daily life [17].

### 5.3 Self-Expression and Social Interaction

Emotion-aware fashion enables new forms of self-expression and social interaction, allowing individuals to communicate their emotional states in creative, dynamic ways.

Emolleia, the wearable kinetic flower display, targets individuals who find it difficult to express emotions, such as shy introverts [15]. The system's eight pre-defined animations, triggered by facial expressions, provide a non-verbal means of emotional expression. User surveys revealed potential applications in enhancing conversation efficiency and potentially in medical care or counseling for children with special conditions such as autism, helping them communicate their willingness to talk or emotional status [15].

Mura's exploration of wearable technologies for emotion communication emphasizes the augmentation of natural emotional expression [29]. By adding artificial visual responses to the physiological visual responses of the body through garments and accessories, wearable technologies create interactively changing appearances that enhance users' abilities to express emotions [29]. The dynamic visual compositions, defined by users and provided by computational processes, offer new dimensions of emotional expression [29].

The Emotional Wardrobe concept proposes clothing that offers "a personal and provocative definition of self, one which actively involves the wearer in a mutable aesthetic identity" [14], [24]. This vision replaces the fixed physicality of traditional fashion with a constant flux of self-expression and playful psychological experience, enabled by technology's capacity to create responsive, emotionally expressive garments [24].

Iaconesi's work on wearing emotions explores wearable devices as emotional skins—reactive layers that visualize individuals' or groups' emotional configurations [13]. These interactive surfaces generate cognitive processes relevant for social communication, knowledge dissemination, and education, demonstrating emotion-aware fashion's potential beyond personal expression to collective emotional awareness [13].

## 6. Key Findings and Comparative Analysis

The reviewed literature reveals significant advances in emotion-aware smart fashion across multiple dimensions. Table 1 provides a comparative overview of key systems, their emotion detection methods, output modalities, and reported outcomes.

**Table 1: Comparative Analysis of Emotion-Aware Smart Fashion Systems**

| System | Emotion Detection | Output Modality | Key Performance Metrics | Primary Application |
|--------|------------------|-----------------|------------------------|---------------------|
| Nanofibre Clothing [1] | Physiological (pulse, temp, sweat) | Adaptive garment properties | 97.8% accuracy, 98.1% precision | General well-being |
| Smart Scarf [12] | Physiological (HR, skin temp) | Color-changing LEDs | User satisfaction in emotion tracking | Mental health support |
| Emotion-Reacting Wear [3], [4] | Facial expressions | RGB-LEDs, audio (music) | Variable accuracy by emotion | Mental health, communication |
| Smart Accessory [5] | EMG (facial muscles) | RGB-LED patterns | Successful transmission of positive emotions | Communication (masked faces) |
| Emolleia [15] | Facial expressions | Kinetic flower animations | Significant valence/arousal differences | Self-expression, social interaction |
| SWARM [9] | Physiological (HR, perspiration) | Heat, vibration, audio, light | User preference data for modalities | Emotion management, empathy |
| Interactive Clothing [16], [18] | Proximity sensors | LEDs (proximity-based) | Significant emotional response differences | Interpersonal communication |
| Smart Shawl [27] | EDA, pressure sensors | Light, vibration | Stress reduction confirmed | Emotion regulation |
| SCAARF [21] | Not specified | Subtle interventions via scarf | Effective anxiety relief (qualitative) | Anxiety management |

Several patterns emerge from this comparative analysis:

**Emotion Detection Approaches**: Physiological signal-based methods dominate the field, with heart rate and skin conductance being the most commonly employed modalities. These methods offer continuous, passive monitoring without requiring user input. Facial expression recognition provides an alternative that aligns with natural human communication but faces challenges with accuracy for non-happiness emotions and requires camera integration. Movement-based approaches remain less explored but offer potential for more naturalistic emotion detection.

**Performance Metrics**: The nanofibre-based system achieved the highest reported accuracy (97.8%) for emotion classification [1]. However, most studies report qualitative user feedback rather than quantitative performance metrics. This reflects the field's current emphasis on design exploration and user experience over rigorous technical evaluation. The facial expression recognition system revealed a common challenge: while happiness was reliably detected, other emotions showed lower accuracy [4].

**Output Modalities**: Visual feedback through LEDs represents the most prevalent output modality, appearing in seven of the nine systems analyzed. This preference likely reflects LEDs' low power consumption, ease of integration, and immediate visual impact. Kinetic actuation and haptic feedback offer more sophisticated but technically challenging alternatives. The SWARM project's finding that different modalities serve different functions—heat and music for mood modification, vibration for alerts—suggests that multimodal systems may be most effective [9].

**Application Focus**: Mental health and emotion regulation applications dominate the field, reflecting growing awareness of mental health challenges and the potential for wearable technology to provide continuous support. Interpersonal communication represents a secondary focus, with several systems designed to make emotional states visible to others. Self-expression applications remain less common but demonstrate creative potential.

**Design Integration**: Systems vary significantly in their approach to fashion integration. Some, like the emotion-reacting wear, explicitly adopt fashion-forward design concepts (retro-futurism) [3], [4]. Others, like the Smart Scarf, prioritize comfort and everyday wearability [12]. The modular approach employed by SWARM offers a middle path, enabling customization while maintaining aesthetic appeal [9].

**Evaluation Methods**: User studies typically involve small sample sizes (10-50 participants) and short durations (days to weeks). Kansei engineering methods have been employed to assess emotional impact [16], [17], [18]. The field would benefit from larger-scale, longer-term studies to assess sustained usage, user acceptance, and real-world effectiveness.

## 7. Discussion

### 7.1 Technical Achievements and Limitations

The reviewed literature demonstrates substantial technical progress in emotion-aware smart fashion. The achievement of 97.8% accuracy in emotion classification using physiological signals represents a significant milestone [1]. The successful integration of diverse sensing modalities—from nanofibre-embedded sensors to facial expression recognition cameras—demonstrates the field's technical maturity.

However, several technical limitations persist. Facial expression recognition systems struggle with distinguishing subtle emotional states, with many expressions misidentified as neutral [4]. This limitation reflects broader challenges in affective computing: the complexity of human emotions, individual differences in emotional expression, and the context-dependency of emotional states. The reliance on discrete emotion categories (happy, sad, angry, neutral) may oversimplify the continuous, multidimensional nature of human affect.

Sensor integration remains challenging. While nanofibre technology and conductive fabrics enable flexible sensor embedding, concerns about waterproofing, durability, and washability persist [11]. The need for battery power and electronic components creates bulk that can compromise garment aesthetics and comfort. The SWARM project's modular approach offers one solution, but the trade-off between functionality and seamless integration remains unresolved [9].

Real-time processing requirements pose computational challenges. The emotion-reacting wear's use of cloud-based APIs (Microsoft Azure Cognitive Services) raises questions about latency, connectivity dependence, and privacy [4]. The "Sixth Sense Garment" framework's emphasis on edge-AI processing addresses these concerns by enabling on-device computation, but this approach requires more sophisticated hardware integration [6].

### 7.2 Design and User Experience Challenges

The integration of technology into fashion presents unique design challenges. As Wang et al. observed, technology-oriented clothing can lack humanistic emotion, creating garments that are functionally sophisticated but emotionally unsatisfying [17]. This tension between technical capability and emotional resonance represents a fundamental challenge for the field.

User acceptance depends on multiple factors beyond technical functionality. Aesthetic appeal, comfort, social acceptability, and perceived value all influence whether individuals will adopt emotion-aware fashion. The Smart Scarf's positive user evaluation demonstrates that carefully designed systems can achieve acceptance [12]. However, the limited duration of most user studies (days to weeks) leaves questions about long-term adoption unanswered.

The visibility of emotional states raises complex social and psychological questions. While some applications aim to make emotions visible to others (interpersonal communication), this transparency may not always be desirable. The BioWear project explicitly raises questions about communication boundaries [8]. Users may want control over when and how their emotional states are displayed, suggesting the need for privacy controls and user agency in emotion-aware fashion systems.

The diversity of user needs and preferences presents another challenge. The SWARM project's finding that different users prefer different output modalities (heat, music, vibration) suggests that one-size-fits-all approaches may be inadequate [9]. Customization and personalization capabilities may be essential for widespread adoption.

### 7.3 Ethical and Privacy Considerations

Emotion-aware fashion systems collect intimate personal data about users' emotional states, raising significant privacy concerns. The continuous monitoring of physiological signals, facial expressions, or movement patterns creates detailed records of users' emotional lives. The storage, transmission, and potential sharing of this data require careful ethical consideration.

The "Sixth Sense Garment" framework's emphasis on edge-AI processing for privacy represents one approach to these concerns [6]. By processing data on-device rather than transmitting it to cloud servers, this approach minimizes privacy risks. However, even local processing raises questions about data access, user control, and potential misuse.

The use of emotion-aware fashion in vulnerable populations (children, individuals with mental health conditions, people with disabilities) requires particular ethical attention. While these populations may benefit significantly from emotion-aware systems, they may also be more susceptible to privacy violations or manipulation. The application of Emolleia for children with autism, for example, offers potential benefits but also raises questions about consent and autonomy [15].

The potential for emotion-aware fashion to influence rather than merely reflect emotional states creates additional ethical considerations. Systems designed for emotion regulation actively intervene in users' emotional experiences. While this intervention may be beneficial (anxiety relief, stress reduction), it also raises questions about emotional authenticity and the medicalization of normal emotional variation.

## 8. Future Directions and Recommendations

The reviewed literature points toward several promising directions for future research and development in emotion-aware smart fashion.

**Sustainable and Circular Design**: The "Sixth Sense Garment" framework's integration of circular economy principles with emotion-aware functionality represents an important direction [6]. Future systems should address the environmental impact of electronic components, emphasizing modular design for repair and upgrade, recyclable materials, and extended product lifetimes. The concept of "aesthetics-on-demand" and "care-by-design" offers a path toward sustainable emotion-aware fashion [6].

**Multimodal Emotion Recognition**: Combining multiple sensing modalities (physiological signals, facial expressions, movement, voice) may improve emotion recognition accuracy and robustness. Current systems typically employ one or two modalities; future systems could integrate diverse data sources to create more comprehensive emotional assessments.

**Personalization and Adaptation**: Emotion expression and regulation needs vary significantly across individuals. Future systems should incorporate machine learning approaches that adapt to individual users' emotional patterns, preferences, and needs. The white shark optimization approach employed by Qishu demonstrates the potential for adaptive algorithms [1].

**Long-term Evaluation**: The field requires larger-scale, longer-term studies to assess sustained usage, real-world effectiveness, and potential unintended consequences. Most current studies involve small samples and short durations. Longitudinal research could reveal how emotion-aware fashion impacts users' emotional awareness, regulation skills, and social relationships over time.

**Context-Aware Systems**: Emotions are inherently context-dependent. Future systems should incorporate contextual information (location, activity, social situation) to improve emotion recognition accuracy and provide appropriate responses. The integration of emotion-aware fashion with broader IoT ecosystems could enable this contextual awareness.

**Standardization and Interoperability**: As the field matures, standards for emotion data formats, communication protocols, and evaluation methods would facilitate comparison across systems and enable interoperability. The "Internet of Clothes" concept proposed by Wang et al. suggests a future where emotion-aware garments form interconnected networks [16].

**Inclusive Design**: Future research should explicitly address diverse user populations, including different age groups, cultural backgrounds, body types, and abilities. The SWARM project's attention to universal design considerations, including users with vision/hearing impairments and autism, provides a model for inclusive approaches [9].

**Theoretical Development**: The field would benefit from more robust theoretical frameworks linking emotion detection methods, output modalities, and psychological outcomes. While Kansei engineering and affective computing provide foundations, emotion-aware fashion requires theories that specifically address the unique affordances and constraints of wearable, fashionable systems.

## 9. Conclusion

Emotion-aware smart fashion represents a significant convergence of affective computing, wearable technology, and fashion design. The reviewed literature demonstrates substantial progress across multiple dimensions: emotion detection technologies achieving high accuracy, innovative approaches to wearable integration, and diverse applications in mental health, interpersonal communication, and self-expression.

Key achievements include the development of physiological sensing systems with 97.8% emotion classification accuracy [1], the successful integration of emotion detection into aesthetically appealing fashion items [3], [4], [12], and demonstrated effectiveness in applications ranging from anxiety relief [21] to enhanced interpersonal communication [18]. The field has evolved from early conceptual explorations [14], [24] to functional prototypes with validated user benefits [12], [15], [27].

However, significant challenges remain. Technical limitations in emotion recognition accuracy, particularly for subtle emotional states, require continued research. Design challenges in balancing technical functionality with aesthetic appeal and user comfort persist. Ethical concerns about privacy, data security, and emotional autonomy demand careful attention as systems become more sophisticated and widely deployed.

The future of emotion-aware smart fashion lies in sustainable, personalized, context-aware systems that respect user privacy while providing meaningful support for emotional awareness, regulation, and communication. The integration of edge-AI processing [6], modular design approaches [9], and circular economy principles [6] points toward more responsible and sustainable implementations. As the field matures, emotion-aware fashion has the potential to fundamentally transform how individuals understand, manage, and communicate their emotional lives, creating garments that are not merely worn but that actively participate in emotional well-being.

The intersection of emotional states, wearable technology, and fashion design continues to offer rich opportunities for innovation. By addressing current limitations while building on demonstrated successes, researchers and designers can create emotion-aware fashion systems that are technically sophisticated, aesthetically compelling, ethically responsible, and genuinely beneficial to users' emotional health and social connections.

## 10. References

[1] Qishu, "Implementation method of intelligent emotion-aware clothing system based on nanofibre technology," *Industria Textila*, 2024. DOI: [10.35530/it.075.01.202379](https://doi.org/10.35530/it.075.01.202379)

[2] Jiang, "Movement-based interactive textiles design for emotion regulation," *Design Journal*, 2021. DOI: [10.1080/14606925.2021.1903678](https://doi.org/10.1080/14606925.2021.1903678)

[3] Kai et al., "Emotion-Reacting Wear Based on Facial Expression Analysis," *International Symposium on Affective Science and Engineering*, 2022. DOI: [10.5057/isase.2022-c000037](https://doi.org/10.5057/isase.2022-c000037)

[4] ISHIUCHI et al., "Emotion-reacting fashion design: intelligent garment and accessory recognizing facial expressions," 2022. DOI: [10.5821/conference-9788419184849.29](https://doi.org/10.5821/conference-9788419184849.29)

[5] Ishiuchi et al., "Design and Development of a Smart Fashion Accessory – Communicating Positive Facial Expressions Hidden by Face Masks –"

[6] Burnstine, "The Sixth Sense Garment: A State-of-the-Art Framework for Sustainable Neurofashion," 2025. DOI: [10.20944/preprints202508.1131.v1](https://doi.org/10.20944/preprints202508.1131.v1)

[7] Ugur, "Wearing Embodied Emotions: A Practice Based Design Research on Wearable Technology," 2013.

[8] Pailes-Friedman, "BioWear: a kinetic accessory that communicates emotions through wearable technology," *International Symposium on Wearable Computers*, 2015. DOI: [10.1145/2800835.2809435](https://doi.org/10.1145/2800835.2809435)

[9] Williams et al., "SWARM: An Actuated Wearable for Mediating Affect," *Tangible and Embedded Interaction*, 2015. DOI: [10.1145/2677199.2680565](https://doi.org/10.1145/2677199.2680565)

[10] Farahi, "HEART OF THE MATTER: Affective Computing in Fashion and Architecture." DOI: [10.52842/conf.acadia.2018.206](https://doi.org/10.52842/conf.acadia.2018.206)

[11] Xia et al., "Design of interactive fashion (IF) related to emotion recognition based on detection of physiological signal data," 2017. DOI: [10.15406/JTEFT.2017.02.00048](https://doi.org/10.15406/JTEFT.2017.02.00048)

[12] Almukadi, "Smart Scarf: An IOT-based Solution for Emotion Recognition," *Engineering, Technology & Applied Science Research*, 2023. DOI: [10.48084/etasr.5952](https://doi.org/10.48084/etasr.5952)

[13] Iaconesi, "Wearing Emotions: Physical Representation and Visualization of Human Emotions Using Wearable Technologies," 2010. DOI: [10.1109/IV.2010.38](https://doi.org/10.1109/IV.2010.38)

[14] Stead et al., "The Emotional Wardrobe," *Ubiquitous Computing*, 2004. DOI: [10.1007/S00779-004-0289-4](https://doi.org/10.1007/S00779-004-0289-4)

[15] Zhuang et al., "Emolleia – Wearable Kinetic Flower Display for Expressing Emotions," *International Conference on Tangible, Embedded, and Embodied Interaction*, 2022. DOI: [10.1145/3490149.3505581](https://doi.org/10.1145/3490149.3505581)

[16] Wang et al., "Interactive technology embedded in fashion emotional design: Case study on interactive clothing for couples," *International Journal of Clothing Science and Technology*, 2018. DOI: [10.1108/IJCST-09-2017-0152](https://doi.org/10.1108/IJCST-09-2017-0152)

[17] Wang et al., "Design optimization for interactive parent-child clothing: integration of iot technology entities and emotional virtual bodies," 2018. DOI: [10.21278/IDC.2018.0302](https://doi.org/10.21278/IDC.2018.0302)

[18] Weizhen et al., "Human-centred design blending smart technology with emotional responses: Case study on interactive clothing for couples," 2017.

[19] "Métodos e Ferramentas para Avaliação Afetiva de Artefatos Vestíveis: Uma Revisão da Sistemática da Literatura," 2022. DOI: [10.5151/9786555502145-08](https://doi.org/10.5151/9786555502145-08)

[20] Chen et al., "Wearable Affective Robot," 2018.

[21] Lopes et al., "SCAARF: a subtle conditioning approach for anxiety relief facilitation," *Mobile and Ubiquitous Multimedia*, 2019. DOI: [10.1145/3365610.3368417](https://doi.org/10.1145/3365610.3368417)

[22] Rikanovic et al., "The Significance of Emotional and Sustainable Values in Smart Clothing."

[23] Cho et al., "An analysis of consumer emotion for product planning of smart clothing," 2014. DOI: [10.14695/KJSOS.2014.17.3.49](https://doi.org/10.14695/KJSOS.2014.17.3.49)

[24] Stead, "'The emotional wardrobe': a fashion perspective on the integration of technology and clothing," 2005.

[25] Dejene, "Wearable smart textiles for mood regulation: A critical review of emerging technologies and their psychological impacts," *Journal of Industrial Textiles*, 2025. DOI: [10.1177/15280837251314190](https://doi.org/10.1177/15280837251314190)

[26] Yan et al., "EmoGlass: an End-to-End AI-Enabled Wearable Platform for Enhancing Self-Awareness of Emotional Health," *CHI Conference on Human Factors in Computing Systems*, 2022. DOI: [10.1145/3491102.3501925](https://doi.org/10.1145/3491102.3501925)

[27] Jiang et al., "Exploring the design of interactive smart textiles for emotion regulation," *International Conference on Human-Computer Interaction*, 2020. DOI: [10.1007/978-3-030-59987-4_22](https://doi.org/10.1007/978-3-030-59987-4_22)

[28] Cass, "Anouk Wipprecht: dynamic dresses merge high fashion and technology [Resources]," *IEEE Spectrum*, 2016. DOI: [10.1109/MSPEC.2016.7419790](https://doi.org/10.1109/MSPEC.2016.7419790)

[29] Mura, "Wearable technologies for emotion communication," 2008.

[30] Gilgen et al., "From Wearables to Soft-Wear: Developing Soft User Interfaces by Seamlessly Integrating Interactive Technology into Fashionable Apparel," *International Conference of Design, User Experience, and Usability*, 2014. DOI: [10.1007/978-3-319-07638-6_25](https://doi.org/10.1007/978-3-319-07638-6_25)
