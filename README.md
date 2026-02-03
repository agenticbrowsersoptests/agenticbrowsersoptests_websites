# Test Websites for Same-Origin Policy and Agentic Browser Security Experiments

This repository contains (anonymized) test websites used in 
the experiments described in the USENIX Security 2026 
submission titled "Agentic Browsers and the Same-Origin Policy".

These websites must be hosted on two separate domains for 
testing. In this repository, we have replaced the domains 
with anonymized placeholders `A.com` and `B.com` -- these must 
be replaced with real domains hosting the websites for them
to function correctly.

The prompts used to test agentic browsers on these websites
are included in full in Section 3.3 of the paper.

## Website Summaries

`A.com`
* `bob1.html` : Used for additional experiments in Section 4.3
* `bob2.html` : Used for additional experiments in Section 4.3
* `complexpage.php` : Used as described in Section 3.3
* `cookie.php` : Used to set cookie for personalized content tests
* `inner.html` : Used as described in Section 3.3
* `input.html` : Used as described in Section 3.3
* `input2.html` : Used as described in Section 3.3
* `other.html` : Used as described in Section 3.3
* `outer-cross.html` : Used as described in Section 3.3
* `outer-same.html` : Used as described in Section 3.3
* `poc.html` : Used for proof-of-concept cross-origin outer-from-inner-frame data theft (Figure 2)
* `poc2.html` : Variant of `poc.html` which attempts a full prompt injection
* `poc3-frame.html` : Used with `B.com/poc3.html`
* `poc4-frame.html` : Used with `B.com/poc4.html`
* `summary.php` : Form submission destination for proofs-of-concept

`B.com`
* `bob1.html` : Used for additional experiments in Section 4.3
* `bob2.html` : Used for additional experiments in Section 4.3
* `inner.html` : Used as described in Section 3.3
* `other.html` : Used as described in Section 3.3
* `poc3.html` : Used for proof-of-concept cross-origin inner-from-outer-frame data theft
* `poc4.html` : Used for proof-of-concept JavaScript injection attack (Figure 3)
* `summary.php` : Form submission destination for proofs-of-concept
