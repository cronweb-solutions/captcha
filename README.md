<p align="center">
  <h1 align="center">CWCaptcha</h1>
  <p align="center">
    <strong>Adaptive Human Verification & Anti-Abuse Infrastructure</strong>
  </p>

  <p align="center">
    Private security infrastructure.
  </p>
</p>

---

## Human verification beyond a puzzle

**CWCaptcha** is Cronweb's privately operated human-verification and
adaptive anti-abuse layer.

It combines interactive verification with server-side risk analysis,
rate limiting, replay resistance, domain isolation, action binding and
security-event intelligence.

CWCaptcha is designed to protect sensitive web actions while keeping
legitimate-user interaction fast, responsive and privacy-conscious.

> Built for hostile traffic. Designed for legitimate humans.

---

## Security architecture

CWCaptcha uses a defense-in-depth verification model.

### Adaptive Risk Analysis

Requests are evaluated using multiple privacy-conscious signals including
request velocity, challenge history, failure patterns, session continuity,
interaction timing and local abuse intelligence.

### Replay-Resistant Verification

Successful challenge responses produce short-lived verification tokens
designed for one narrowly defined action.

Tokens are bound to their intended website and action and are validated
server-side.

### Domain & Action Binding

A verification created for one protected domain or application action
cannot simply be reused for another.

### Layered Rate Limiting

CWCaptcha applies multiple independent request controls across challenge
creation, solving, verification and administrative operations.

### Server-Owned Challenge State

Authoritative CAPTCHA answers and security decisions remain server-side.
Browser JavaScript is never treated as the trust boundary.

---

## Verification experiences

CWCaptcha supports several adaptive verification methods.

### Smart Verification

Low-friction verification for requests that do not require an
interactive challenge.

### Slider Puzzle

Dynamically generated image alignment challenges with randomized
geometry and server-side validation.

### Image Recognition

Randomized image-selection challenges backed by a privately managed
challenge library.

### Procedural Spatial Logic

Generated visual reasoning tasks using combinations of shape, size,
position, pattern, outline, color and spatial relationships.

### Ordered Icon Verification

Procedurally generated icon scenes with randomized icon selection,
placement, scale, rotation, colors and background interference.

### Audio Verification

A listen-and-type alternative for visitors who cannot effectively use
visual verification.

---

## Adaptive verification

CWCaptcha does not rely on one fixed CAPTCHA experience.

Depending on risk and website policy, a request may be:

- verified with minimal interaction
- presented with an interactive challenge
- escalated to stronger verification
- rate limited
- denied

Challenge difficulty and verification strategy can therefore change
according to request context.

---

## Local defense

CWCaptcha includes local anti-abuse controls designed to reduce reliance
on commercial IP-intelligence services.

Security signals may include:

- short-window request velocity
- long-window traffic patterns
- failed verification history
- repeated token failures
- network-prefix activity
- abnormal interaction timing
- per-domain abuse history
- service-wide traffic limits
- optional locally operated security intelligence

External reputation providers can remain optional.

---

## Privacy-conscious by design

CWCaptcha is designed as private infrastructure rather than an
advertising, profiling or analytics network.

Security data is retained only where it materially contributes to
verification, abuse prevention, operational diagnostics or security
analysis.

No CAPTCHA should be treated as proof that a visitor is permanently
trustworthy.

A successful verification authorizes only the intended protected
action.

---

## Web3 & blockchain direction

CWCaptcha's core verification infrastructure currently relies on
server-side cryptographic verification, short-lived tokens, replay
protection, domain binding and action binding.

Future integration areas include:

**Web3 authentication integration**
- wallet-based identity assertions
- signed challenge verification
- optional decentralized identity workflows

**Blockchain-verifiable security**
- cryptographically verifiable audit anchoring
- tamper-evident security-event commitments
- independently verifiable integrity proofs

These capabilities are architectural roadmap areas and are not required
for CWCaptcha's current CAPTCHA verification model.

---

## Built for private infrastructure

CWCaptcha is not operated as a public CAPTCHA SaaS.

It was designed for centrally protecting websites operated within the
Cronweb network.

The production source code, risk algorithms, challenge internals,
security thresholds, infrastructure configuration and operational
credentials are intentionally not published in this repository.

This repository provides public information about the platform only.

---

## Security philosophy

CWCaptcha follows one central principle:

> **A CAPTCHA solve permits one narrowly defined action attempt; it does
> not permanently mark a visitor as trustworthy.**

Its security model combines:

**Challenge**
+
**Risk Analysis**
+
**Rate Limiting**
+
**Replay Protection**
+
**Domain Binding**
+
**Action Binding**
+
**Security Logging**
+
**Outcome Feedback**

---

## Technology

CWCaptcha's private service architecture is built around:

Production infrastructure and implementation details remain private.

---

## Security notice

CWCaptcha is designed as one layer of a broader application-security
architecture.

Protected websites remain responsible for authentication,
authorization, CSRF protection, application-level rate limiting and
business-rule validation.

---

## Privacy

Read the public CWCaptcha privacy notice:

**[CWCaptcha Privacy Policy](./PRIVACY.md)**

---

## About Cronweb

CWCaptcha is private verification infrastructure.

**CWCaptcha — Adaptive Human Verification & Anti-Abuse Infrastructure**
