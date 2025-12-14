#### Overview

I/O is a **multiplatform audio graph engine**, written entirely in ***Swift***, designed to offer a flexible and high-performance system for creating, processing, and routing audio in real time. The engine provides a comprehensive set of tools to select audio sources, apply effects, generate visualizations, and more. All operations are executed within an **audio context**, conceived to enable ***modular*** and scalable routing. Core operations are performed through *nodes*, which are linked together to form a processing graph. These nodes can be arranged into ***simple chains or more complex networks***, connecting their inputs and outputs to establish custom signal paths. Typically, processing begins with one or more sources delivering samples at extremely small time intervals—often tens of thousands per second. The output of each node can be routed to others, mixing, transforming, or processing the audio signal in different ways, enabling sophisticated paths for ***production, analysis, or final rendering***. Thanks to its modular architecture and optimized implementation in ***Swift***, I/O combines design clarity with high performance, ensuring accuracy and low latency across multiple environments.

#### License

This project is distributed under a license that allows its use, modification, and distribution, provided that the specified terms are respected (http://opensource.org/licenses/mit-license.php)

Copyright © 2019 - 2027 - ***Comdigis***, *Buenos Aires, Argentina*.
