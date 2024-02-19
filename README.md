# CS-230
CS-230 Operating Platforms
Adam Vosburg

The Gaming Room client was looking to expand their existing Draw It or Lose It game from being just a web-based application to also support mobile platforms like iOS and Android. They wanted to design the expanded software architecture and data considerations to support this cross-platform approach while ensuring a seamless user experience across devices. My software design document details recommendations on hosting infrastructure to leverage, OS/architecture options per platform, data storage structures, memory management, distributed systems networking, and security best practices.

Particularly Well Executed Aspect

I believe I developed an effective overview of the core technical components, guiding architectural principles, and infrastructure integration points critical for the client to consider when expanding software support across web, mobile, and distributed systems. Capturing infrastructure elements like operating platforms and individual considerations per target device ecosystem demonstrates attentiveness to how client goals translate to tangible system building blocks.

Helpful for Coding

Thinking through data structures and compartmentalizing functional modules into microservices aids implementation organization when translating designs to actual code. Defining these logical separations upfront streamlines development by avoiding tightly coupled elements that increase testing and deployment burdens. Diagramming relationships between entity classes also facilitates programming model integrity as concrete child classes inherit from established abstraction parent schemas.

Area to Improve

Given more time, I would like to expand on UI/UX specifications for the mobile experience since optimizing for smaller touch-driven form factors warrants dedicated design considerations beyond porting website flows. Tailoring responsive visual layouts and intuitive gesture-based controls improves adoption across phone and tablet users. I should mock up core wireframes addressing information architecture, minimal tap targets, easy-to-read layouts, and error handling to enable effortless cross-platform usage.

Interpreting User Needs

I aimed to directly map specified functional goals like game/team management, preventing duplicate names, and maintaining data integrity into technical implementations through a Singleton GameService, external iterator patterns, and relational storage structures. This connects user capabilities to underlying architectures. Planning environments spanning on-premise to cloud platforms aligned with their expansion vision. Considering scale, security, and device ubiquity preserves a consistent experience as the system and user base grow per their roadmap.

Software Design Approach

I believe applying proven patterns upfront aids a quick understanding of intent while allowing flexibility on underlying implementations for developers. Decomposing larger functionality into API-driven microservices and then integrating through lightweight protocols like REST enables building out complex systems incrementally yet holistically. Defining data schemas and flows first gives a frame for downstream activities like UI design. I'd leverage similar techniques of modularization, abstraction through patterns, diagramming domain models, and emphasizing traceability between user and technical perspectives.

