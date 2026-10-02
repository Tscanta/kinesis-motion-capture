# Kinesis

**Kinesis** is a markerless motion-capture and AI-assisted rotoscoping
concept built to make human motion easier to capture and turn into
digital animation.

The project explores a simple idea: instead of relying on expensive
motion-capture suits, markers, or dedicated studio equipment, use
computer vision to detect human movement from a camera and convert that
movement into usable motion data.

## What Kinesis Does

The prototype captures a performer through a camera, detects body
landmarks, processes the movement data, and sends the resulting motion
information toward a 3D animation workflow.

The intended pipeline is:

``` text
Camera
  |
  v
Pose Detection
  |
  v
Motion Processing
  |
  v
Real-Time Data Streaming
  |
  v
Unity / 3D Character
```

The same pose information can also be used as a foundation for
AI-assisted rotoscoping, helping animators obtain tracked body positions
instead of manually identifying them frame by frame.

## Current Prototype

The current prototype was developed under the constraints of the
hackathon and is being demonstrated using a **laptop webcam**. We
currently do not have the iQOO phone, so the phone-based capture
pipeline is part of our planned next stage rather than a completed part
of the prototype.

The prototype demonstrates the core concept of:

-   Camera-based human pose detection
-   Body landmark tracking
-   Motion processing
-   Real-time motion data transfer
-   Unity-based character movement
-   The potential use of pose data for rotoscoping

Because the prototype was built quickly during the hackathon, there are
still implementation issues. The laptop webcam also limits tracking
quality, and the current model can show jitter, delay, and imperfect
responsiveness. Improving smoothing, tracking accuracy, latency, and
character responsiveness is one of the main areas we intend to work on
as development continues.

## Hackathon Context

Kinesis was built as a project for the **iQOO Hackathon 2026 in
Hyderabad**.

The hackathon gave us a limited development window to turn the idea into
a working proof of concept. Rather than presenting only a concept, we
focused on getting an end-to-end pipeline running and demonstrating the
core interaction between human movement and a digital character.

The current prototype should therefore be viewed as an early technical
proof of concept rather than the finished product.

Our longer-term direction is to develop Kinesis into a complete software
platform that developers and creators can actually integrate into their
workflows.

## Target Users

Kinesis is being designed for:

-   Indie game developers
-   3D animators
-   VFX and rotoscoping artists
-   Students and independent creators
-   Small animation and game-development teams

The goal is to reduce the hardware and setup barrier that can make
professional motion capture difficult for smaller teams.

## Planned Direction

The next stage of Kinesis is to explore using an iQOO phone as the
portable capture device:

``` text
iQOO Camera
    |
    v
Pose Detection
    |
    v
Motion Processing
    |
    v
Motion Data
    |
    v
Laptop / Unity
    |
    v
3D Character
```

We want to improve the system in several areas:

-   More responsive motion tracking
-   Better motion smoothing
-   Reduced latency
-   Improved pose accuracy
-   More complete body-joint tracking
-   Better character retargeting
-   A cleaner developer-facing software workflow
-   Rotoscoping-oriented tooling

The broader goal is to grow Kinesis beyond the hackathon prototype and
eventually turn it into a usable software product and potential startup.

## Demo and Explanation Videos

### Live Prototype Demo

This video shows the current prototype being tested live, including the
camera-based tracking and character workflow.

https://youtu.be/w6Gxm-Jq2dA

### Project Explanation

A longer explanation of the Kinesis concept, its intended workflow, and
the problem it is designed to address.

https://youtu.be/9CF5mg4FbvM

### Short Project Overview

A short-form overview of the project.

https://www.youtube.com/shorts/GmdXXUH7yjw

## Built During the Hackathon

Kinesis is intentionally documented as a work-in-progress.

The current implementation represents what we were able to build and
demonstrate within the hackathon timeframe. The limitations shown in the
prototype are part of the development process, and the project is
intended to continue evolving after the event.

**Kinesis --- Human Motion. Digital Life.**
