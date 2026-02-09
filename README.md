<p align="center">
  <img width="300" alt="sgrd" src="sigrd.png" />
</p>


---

<p align="center">
  <a href="https://en.wikipedia.org/wiki/Python_(programming_language)"><img src="https://img.shields.io/badge/Python_Based-0D1164"></a>
  <a href="https://www.malwarebytes.com/blog/threats/remote-access-trojan-rat"><img src="https://img.shields.io/badge/RAT-08CB00"></a>
  <a href="https://lolapps-project.github.io/lolapps/Web/discord/" target="_blank"><img src="https://img.shields.io/badge/LOLAPPS-Discord-blue"></a>
  <a href=""><img src="https://img.shields.io/badge/DFIR-Assessment_Purpose-640D5F"></a>
  <a href="https://itsecsummit.events/"><img src="https://img.shields.io/badge/SUMMIT-ITSEC_CTF_Competition_2025-660B05"></a>
  <a href="https://baycysec.org/"><img src="https://img.shields.io/badge/BAYCYSEC-Operation_Baby_Steps-FFFFFF"></a>
</p>

> [!IMPORTANT]
> This repository intentionally contains only this README. The actual Sigurd sample is not published here. Sigurd is a research/forensics artifact with capabilities that could be harmful if misused. Access is restricted and provided only to vetted researchers, instructors, incident responders, and authorized learners under formal agreements.

## [👤] About Sigurd

<p align="justify">
Sigurd is a research-oriented malware sample, specifically a Remote Access Trojan (RAT), used to support digital forensics, incident response training, and CTF-style forensic challenges. It appeared in the ITSEC Asia Cyber Security SUMMIT CTF event. The first known sample of Sigurd was submitted to <a href="https://www.virustotal.com/gui/file/a8ed9231b4128d5aa006daa27034e30f0c2c59ca4b1211b33da63e142e504f91/detection" target="_blank">VirusTotal</a> by CTF participants, which may be relevant to analysts studying its behavior.</p>

<img width="1418" height="1001" alt="image" src="https://github.com/user-attachments/assets/f18e180e-2e1f-4334-b6d0-040a23420ce2" />


## [📃] High-level (Non-Actionable) Summary

<p align="justify">For defensive analysts and instructors, the artifact demonstrates patterns commonly seen in threats and red-team tooling, including (descriptive only):</p>

- Discord-based command-and-control style communications.
- Remote command execution capability guarded by an authorization check.
- A file transformation/encryption pipeline that marks modified files.
- Clipboard capture and remote exfiltration of clipboard contents.
- Keystroke capture (keylogger) with local and remote logging.
- Windows persistence via Registry-key modification.
- Cleanup routines and multiple stealth measures.

> [!TIP]
> This list is intentionally high-level and non-actionable — it does not provide build/run instructions, configuration values, or operational guidance.

## [❓] Who may Request Access

<p align="justify">Access is intended for legitimate defenders and educators: university instructors running isolated labs, DFIR teams performing analysis, security researchers validating detections, and CTF/competition organizers who need controlled challenge artifacts. Requests from individuals or groups without a verifiable institutional affiliation will be subject to stricter vetting or denied.</p>

## [✅] DFIR Lab Offer

<p align="justify">Approved recipients will get a secure, logged transfer of materials tailored to their needs. Typical deliverables include:</p>

- An encrypted sample archive (delivered only after vetting and signed agreements).
- A DFIR lab package (VM snapshot or disk image) that contains the artifact in a contained environment suitable for hands-on analysis.
- A sanitized forensic guide and IOCs to support teaching and detection work.

## [📰] Provenance

- Used in: ITSEC CTF Competition 2025 (forensics final round).
- Public trace: The first version of Sigurd was submitted to VirusTotal by CTF participants.

## [🧪] Development & Future

<p align="justify">Sigurd is an active research artifact and may be enhanced over time for defensive research and teaching. Distribution policy and access controls will remain governed by the maintainers</p>

## [📧] How to Request Access

E-mail `baycysec@gmail.com` with:
- Full name, affiliation, and role.
- Intended use (training / research / CTF).
- Short containment plan (VM provider or snapshot/rollback).

After initial review for 2 weeks, we’ll provide details about agreements and secure transfer.

## [📝] Developer
- [jon-brandy](https://github.com/jon-brandy)
