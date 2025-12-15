#### Overview

I/O is a **multiplatform audio graph engine**, written entirely in ***Swift***, designed to offer a flexible and high-performance system for creating, processing, and routing audio in real time. The engine provides a comprehensive set of tools to select audio sources, apply effects, generate visualizations, and more. All operations are executed within an **audio context**, conceived to enable ***modular*** and scalable routing. Core operations are performed through *nodes*, which are linked together to form a processing graph. These nodes can be arranged into ***simple chains or more complex networks***, connecting their inputs and outputs to establish custom signal paths. Typically, processing begins with one or more sources delivering samples at extremely small time intervals—often tens of thousands per second. The output of each node can be routed to others, mixing, transforming, or processing the audio signal in different ways, enabling sophisticated paths for ***production, analysis, or final rendering***. Thanks to its modular architecture and optimized implementation in ***Swift***, I/O combines design clarity with high performance, ensuring accuracy and low latency across multiple environments.

#### Proposals

I/O provides a structured mechanism for proposing changes, enhancements, or new functionality through a formal proposal process. This process is intended to capture design intent, technical context, and potential impact in a clear and reviewable manner before implementation begins. Proposals may cover architectural changes, new node types, API extensions, performance improvements, or adjustments to existing behavior. All proposals must be submitted using the official [**Proposal Template**](./proposals/proposal-template.md), which defines the required sections for context, motivation, changes, benefits, potential impact, and risks. Using this template ensures consistency, facilitates technical discussion, and helps maintain alignment with the engine’s design principles and long-term roadmap.

Contributors and users are encouraged to review existing proposals before submitting a new one, and to reference the template directly when drafting their submission.

#### License

This project is distributed under a license that allows its use, modification, and distribution, provided that the specified terms are respected (http://opensource.org/licenses/mit-license.php)

Copyright © 2019 - 2027 - ***Comdigis***, *Buenos Aires, Argentina*.
