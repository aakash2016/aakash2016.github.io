---
layout: archive
permalink: /reflections/cse253R/
author_profile: true
---

<div style="display: flex; align-items: center; font-size: 14px; font-family: 'Times New Roman', Times, serif; color:rgb(0, 0, 0); margin-top: 15px;">
    Sharing my Reflections on the courses I took as a Data Science major (MS) student at UCSD
</div>

<div style="justify-content: center; align-items: center; font-family: 'Times New Roman', Times, serif;">
  <div style="flex: 1; font-size: 14px; color: #212f3c;">
    <h3 style="color: #1e3a8a; font-size: 24px; font-family: 'Times New Roman', Times, serif;">CSE253R: ML for Music</h3>
    <p><strong style="color: black; font-size: 16px;">Instructor: Prof. Julian McAuley</strong></p>
    <p style="font-size: 14px; color: #212f3c; text-align: justify;">
      This is a course I took especially to understand how ML gets applied to other domains like music. The course was taught by Prof. McAuley, and I noticed that the way he teaches concepts is starkly different from most other professors. The thing is, he understands what students want, he stresses the pain points where students struggle, and in a no-BS way, his class always focuses on the core elements students need to learn. He made sure not to bore us with the same ML content we’ve been learning in many other classes, but instead focused on the musical aspects of things. 
      <br><br>
      The course delved into the following major topics:
      <ul style="font-size: 14px; color: #212f3c; text-align: justify;">
        <li><strong>Data Structures for Music</strong>: This module covered the basics of sound and music theory, including sampling, digital and analog representations and conversions. I also learned key musical concepts such as pitch, notes, scales, and chord progressions.</li>
        <li><strong>Music Representations</strong>: This covered symbolic representations such as MIDI, sheet music, piano-roll, and ABC notation, as well as continuous representations using techniques like spectrograms, Mel-spectrograms, CQT, and MFCC. The module also overlapped with discussions on music information retrieval.</li>
        <li><strong>Predictive Pipelines for Music</strong>: This module covered model architectures and pipelines for both symbolic and audio-domain representations of music, including 1D-CNNs, Music Transformers, CRNNs, and more. The professor also emphasized the importance of audio augmentation techniques. </li>
        <li><strong>Music Generation</strong>: Prof. covered music generation in depth, including historical approaches to algorithmic composition such as Markov Chains and HMMs. The module also explored both symbolic (using LMs) and continuous (using GANs, VAEs, etc) music generation, both conditioned and unconditioned, along with their respective strengths and limitations. </li>
        <li><strong>SOTA Audio Generation</strong>: This module covered latent-based modeling approaches, including latent waveform and spectrogram modeling. I also learned about prominent <strong>diffusion models</strong> and techniques for sampling and generation from them.</li>
      </ul>
      These topics were supported by numerous case studies exploring these concepts in depth.<br><br>
      Few key-takeways to remember:
      <ul style="font-size: 14px; color: #212f3c; text-align: justify;">
        <li>While we conceptually treat audio as continuous, digital audio used in ML is actually discrete due to sampling and quantization. Continuous representations are closer to how humans perceive music, while symbolic representation is closer to the raw language of music.</li>
        <li><strong>Language models</strong> don’t map to music that naturally: it's not easy to deal with simultaneous or overlapping events + musical events have significant amounts of associated metadata (instrumentation, dynamics, phrasing, etc.). With music the <strong>tokenization</strong> is much more complex!</li>
        <li><strong>CNNs</strong> are <strong>reusable</strong> pattern detectors and are <strong>invariant</strong> to shifts. They can also be used in music extensively. In audio we care about repeated musical patterns and invariance to pitch, timing and tempo. We can use CNNs for both symbolic (piano-rolls) and audio-domain (spectrograms) representations of music. </li>
        <li><strong>Audio Augmentation</strong> can include techniques like random cropping (time), frequency filter, delay, reverberation, etc. They change the acoustic qualities of the piece, but shouldn’t change its label.</li>
        <div style="text-align: center;">
          <figure style="display: inline-block; text-align: center; position: relative;">
            <img src="/assets/images/cse253r.png" alt="CSE 253R" style="width: 500px; height: auto;">
            <figcaption style="font-size: 12px; color: #555;">Music Generation grouped into two main settings.</figcaption>
          </figure>
        </div>
      </ul>
      <p style="font-size: 14px; color: #212f3c; text-align: justify;">
      The homeworks and assignments were comprehensive and offered hands-on experience in applying ML to real problems in the musical domain. These included tasks like spectrogram construction and classification, symbolic music generation using Markov chains, and more. For me, the most rigorous and rewarding part of the course was a leaderboard based competition. It involved challenging tasks such as composer classification, multilabel music tagging, and next-sequence prediction. I spent five straight days working on this assignment, and it was totally worth it. Even though I performed well in only a few of the tasks, the learning experience was immense. <br><br>
      For Assignment 2, we were tasked with generating high-quality music. I worked on unconditioned symbolic music generation. I used a simple <strong>GAN architecture</strong> to produce the following symbolic music piece (converted to mp3 from midi):<br><br>
      </p>
      <div style="text-align: center;">
        <audio controls preload="metadata" style="max-width: 100%;">
          <source src="/assets/audio/wgan_sample.mp3" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
      </div>
    </p>
    <p style="font-size: 14px; color: #ec407a;">Spring 2025</p>
  </div>
</div>
