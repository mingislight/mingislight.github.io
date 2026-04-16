---
layout: post
title: "VPN: The Plug That Brought a Computer Home"
date: 2025-08-21
author: Ming Chu
tags: [VPN, Healthcare IT, Remote Work, Reflection]
image: /assets/img/vpn-connection.png
description: "A simple story of how VPN restored a broken computer and what it means to be connected."
keywords: "VPN, healthcare IT, remote work, domain, IT support, reflection"
---

<div style="text-align: center;">
  <img src="/assets/img/vpn-connection.png" alt="VPN Connection" style="max-width:100%; height:auto; border-radius: 8px;">
</div>

We had a problem.

Some remote computers were set up incorrectly and could no longer connect to the hospital network.

The usual fix was heavy.

Ship the machines back to us.

Wipe them clean.

Put them back into the system.

Send them out again.

That was the plan.

But one day, what looked like an accident turned into a lesson.

Instead of waiting for the computer to be shipped back, I worked on it remotely.

With VPN connected, I removed the computer from the system and rejoined it.

And it worked.

That made me stop and wonder. What exactly is VPN?

A VPN is like a long invisible cable.

It lets a remote computer act as if it is sitting inside the hospital building.

Without VPN, a computer is outside the trusted network.

It cannot be recognized.

It cannot follow the rules.

It loses trust.

With VPN, the computer comes home.

It is recognized.

It is supported.

It can work the way it was meant to.

That small change of approach taught me something.

A computer that is away from its source forgets who it is meant to be.

It cannot do anything about it on its own.

But once it is plugged back in, it knows where it belongs.

That is true for computers.

It is also true for us.

> “I am the vine, and you are the branches. If you stay joined to me, and I stay joined to you, then you will produce lots of fruit. But you cannot do anything without me.”

A computer that is away from its source forgets who it is meant to be and cannot do anything about it.  

But once it is plugged back in, it knows where it belongs.  

---

<div style="border:1px solid #ddd; padding:15px; border-radius:8px; background-color:#f9f9f9;">
  <h3>Technical Notes: Rejoining a Computer to the Domain via VPN</h3>
  <ol>
    <li>Login with a <strong>local administrator account</strong> (an account that works only on that computer).</li>
    <li>Connect to the <strong>VPN</strong>.</li>
    <li>Remove the computer from the domain and put it into a temporary workgroup. Restart.</li>
    <li>Log back in with the local administrator account.</li>
    <li>Delete the old computer record from <strong>Active Directory</strong> (the system that keeps track of computers and users, stored in folders called OUs or Organizational Units).</li>
    <li>Connect to the <strong>VPN</strong> again.</li>
    <li>Rejoin the computer to the domain. Restart.</li>
    <li>Log back in with the local administrator account.</li>
    <li>Place the computer record back into the correct folder (OU) in Active Directory.</li>
    <li>Connect to the <strong>VPN</strong> if not already connected.</li>
    <li>Run <code>gpupdate /force</code> to refresh policies.</li>
    <li>Test login with a <strong>domain account</strong> (a normal user login).</li>
  </ol>
  <p style="font-size:14px; color:#555;">These steps are only meant for IT professionals. The story above is the heart of the lesson.</p>
</div>
