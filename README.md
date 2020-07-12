# CESC

The goal of this challenge is to implement a collaborative editing system. Let's say that we have two users, Alice and Bob, who use the Ava application. For some reason (for example to correct mistake from the AI algorithm), they may edit the ASR transcripts - and we need to handle that without conflicts.
This challenge includes several parts:

- algorithm - the algorithm used to handle the editions from Alice and Bob.
- backend - which will host the algorithm and receive editions from Alice and Bob.
- frontend - which will allow to visualize the algorithm in real time.

You must at least implement a minimal part of the backend part, but after that, given the position you are seeking, you may want to focus more on the frontend part or on the algorithm part or on the backend part. This is completely up to you.
Backend should also include answer to the three questions of the challenge. See the `GET /info` documentation.
