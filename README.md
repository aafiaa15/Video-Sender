# Video-Sender
Tech Stack: Node.js, WebSockets, React,
WebRTC (Peer Connection API)
• Developed a real-time peer-to-peer
video sending application using
WebRTC from sender to receiver.
• Implemented a WebSocket-based
signalling server in Node.js to
handle:
1. createOffer – Establishing
peer connections
2. createAnswer –
Responding to connection
requests
3. addIceCandidate –
Managing ICE candidates
for connectivity
• Built the frontend in React using the
WebRTC PeerConnection API to
enable media streaming.
• Handled ICE candidate exchange
for better NAT traversal and
connection reliability.
• Improved video call stability by
optimizing STUN/TURN server
configurations.
