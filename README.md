<keygen> HTML Tag
1. Overview
The <keygen> tag was an HTML form element used to generate a public–private key pair directly in the user's browser during form submission. It was primarily designed for secure authentication and certificate-based systems.

⚠️ Status: Deprecated and no longer supported in modern browsers.

What the <keygen> Tag Does

Generates a cryptographic key pair in the browser

Stores the private key securely on the client side

Sends the public key to the server as form data

Works only inside an HTML <form>

2. Why the <keygen> Tag Existed

The tag was introduced to make client-side cryptography accessible without JavaScript or third-party libraries.

3. Its goals included:

Simplifying secure authentication

Supporting digital certificates

Reducing cryptographic implementation complexity

Real-World Use Cases (Historical)

Client certificate–based authentication

Enterprise and corporate intranet security

Banking and government web portals

Mutual TLS (two-way SSL) systems

4. Deprecation Notice

The <keygen> tag has been removed from the HTML specification due to:

Inconsistent browser support

Limited configurability

Availability of stronger, flexible APIs

Modern Alternatives

Web Cryptography API (window.crypto.subtle)

WebAuthn

OAuth / OpenID Connect
