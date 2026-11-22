# Basics_spotify

A Spotify backend clone REST API designed to handle secure music streaming workflows, role-based access, and media content delivery.

🛡️ Core Capabilities

• Dual-User System: Differentiates permissions and experiences between standard common users (listeners) and verified artists.
• Bulletproof Security: Protects user accounts via Bcrypt password hashing and manages sessions using stateless JWT tokens.
• Relational Music Catalog: Organizes tracks and creator details utilizing a structured MongoDB Album Schema.
• Cloud Asset Management: Streams track files and serves high-res cover art smoothly through ImageKit integration.

💻 Technology Stack

• Runtime & Framework: Node.js + Express.js
• Database Object Modeling: MongoDB + Mongoose
• Media Optimization CDN: ImageKit IO
