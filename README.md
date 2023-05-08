Download Link: https://assignmentchef.com/product/solved-ve216-homework-5
<br>
<ol>

 <li>(a) [5]Perform partial fraction expansion on a system’s frequency response</li>

</ol>

<em>.</em>

Then use Matlab residue to verify your result. Be careful with the interpretation of Matlab outputs in the case of repeated pole(s).

<ul>

 <li>[5]Based on (a), find the unit impulse response <em>h</em>(<em>t</em>) of this system and use Matlab to plot your answer as a function of t. Then use Matlab impulse to generate a same plot and verify your result.</li>

</ul>

<ol start="2">

 <li>Consider the system in Figure 0502.</li>

</ol>

Figure 0502.

(a) [8]Sketch <em>X<sub>p</sub></em>(<em>ω</em>) for −9<em>π </em>≤ <em>ω </em>≤ 9<em>π </em>for the following values of <em>ω</em><sub>0</sub>.

<ol>

 <li><em>ω</em><sub>0 </sub>= <em>π</em></li>

 <li><em>ω</em><sub>0 </sub>= 2<em>π </em> <em>ω</em><sub>0 </sub>= 3<em>π </em>iv. <em>ω</em><sub>0 </sub>= 5<em>π</em></li>

</ol>

<ul>

 <li>[2]For which of the preceding values of <em>ω</em><sub>0 </sub>is <em>x<sub>p</sub></em>(<em>t</em>) identical? For which of the preceding values of <em>ω</em><sub>0 </sub>will NOT be able to recover the input sinusoidal signal after lowpass filtering <em>x<sub>p</sub></em>(<em>t</em>)?</li>

</ul>

<ol start="3">

 <li>[5]Add a subsystem to Problem 2 (with T undetermined) as shown in Figure 0503(a), assume the final output is a single value Q. As <em>ω </em>changes, Q may change. Determine whether the following two plots 0503(b)(c) are possible for the variation of Q as a function of <em>ω</em>. State your reasoning.</li>

 <li>[5]Given the system in Figure 0504(a) and the Fourier transforms in Figure 0504(b), determine the maximum values for <em>T </em>and <em>A </em>in terms of W such that <em>y</em>(<em>t</em>) = <em>x</em>(<em>t</em>) if <em>s</em>(<em>t</em>) is the impulse train</li>

</ol>

+∞ <em>s</em>(<em>t</em>) = <sup>X </sup><em>δ</em>(<em>t </em>− <em>nT</em>)<em>.</em>

<em>n</em>=−∞

State your reasoning.

Figure 0503(a).

Figure 0503(b).

Figure 0503(c).

<ol start="5">

 <li>[5]Given the system in Figure 0505(a) and the Fourier transform of <em>x<sub>r</sub></em>(<em>t</em>) in Figure 0505(b), sketch the Fourier transform of two different signals <em>x</em>(<em>t</em>) that could have generated <em>x<sub>r</sub></em>(<em>t</em>).</li>

 <li>[12]Consider the system in Figure 0506.</li>

</ol>

If <em>X</em><sub>1</sub>(<em>ω</em>) = 0 for |<em>ω</em>| <em>&gt; </em>2<em>W </em>and <em>X</em><sub>2</sub>(<em>ω</em>) = 0 for |<em>ω</em>| <em>&gt; W</em>. For the following inputs <em>x</em>(<em>t</em>), find the ranges for the cutoff frequency <em>W<sub>c </sub></em>in terms of <em>T </em>and <em>W </em>and find the maximum values of <em>T </em>and <em>A</em>, such that <em>x<sub>r</sub></em>(<em>t</em>) = <em>x</em>(<em>t</em>).

<ul>

 <li><em>x</em>(<em>t</em>) = <em>x</em><sub>1</sub>(<em>t </em>− <em>π/</em>2) + <em>x</em><sub>2</sub>(<em>t</em>)</li>

 <li><em>x</em>(<em>t</em>) = <em>x</em><sub>1</sub>(<em>t</em>)<em>x</em><sub>2</sub>(<em>t</em>)</li>

 <li><em>x</em>(<em>t</em>) = <em>dx</em><sub>2</sub>(<em>t</em>)<em>/dt</em></li>

 <li><em>x</em>(<em>t</em>) = <em>x</em><sub>2</sub>(<em>t</em>)cos(2<em>Wt</em>)</li>

</ul>

<ol start="7">

 <li>[5]Suppose we have the system in Figure 0507(a) and 0507(b), in which <em>x</em>(<em>t</em>) is sampled with an impulse train. Sketch <em>x<sub>p</sub></em>(<em>t</em>), <em>y</em>(<em>t</em>) and <em>w</em>(<em>t</em>). State your reasoning.</li>

 <li>We discussed the effect of a loss of synchronization in phase between the carrier signals in the modulator and demodulator in sinusoidal amplitude modulation. We showed that the output of the demodulation is attenuated by the cosine of the phase difference, and in particular, when the modulator and demodulator</li>

</ol>

Figure 0504(a).

Figure 0504(b).

Figure 0505(a).

Figure 0505(b).

have a phase difference of <em>π/</em>2, the demodulator output is zero. As we demonstrate in this problem, it is also important to have frequency synchronization between the modulator and demodulator.

Consider the amplitude modulation and demodulation systems with <em>θ<sub>c </sub></em>= 0 and with a change in the frequency of the modulator carrier so that

<em>w</em>(<em>t</em>) = <em>y</em>(<em>t</em>)cos<em>ω<sub>d</sub>t</em>

where

<em>y</em>(<em>t</em>) = <em>x</em>(<em>t</em>)cos<em>ω<sub>c</sub>t</em>

Figure 0506.

Figure 0507(a).

Figure 0507(b).

Let us denote the difference in frequency between the modulator and demodulator as ∆<em>ω </em>(i.e., <em>ω<sub>d </sub></em>− <em>ω<sub>c </sub></em>= ∆<em>ω</em>). Also assume that <em>x</em>(<em>t</em>) is band limited with <em>X</em>(<em>jω</em>) = 0 for |<em>ω</em>| ≥ <em>ω<sub>M</sub></em>, and assume that the cufoff frequency <em>ω<sub>co </sub></em>of the lowpass filter in the demodulator satisfies the inequality

<em>ω<sub>M </sub></em>+ ∆<em>ω &lt; ω<sub>co </sub>&lt; </em>2<em>ω<sub>c </sub></em>+ ∆<em>ω </em>− <em>ω<sub>M</sub></em>

<ul>

 <li>[5] Show that the output of the lowpass filter in the demodulator is proportional to <em>x</em>(<em>t</em>)cos(∆<em>ωt</em>).</li>

 <li>[5] If the spectrum of <em>x</em>(<em>t</em>) is that shown in figure below, sketch the spectrum of the output of the demodulator.</li>

</ul>

<em>X</em>(<em>jω</em>)

<ol start="9">

 <li>[5] (This problem is related to how AM radios work.) The signal <em>x</em>(<em>t</em>) = sinc(<em>t/π</em>) is modulated to form <em>y</em>(<em>t</em>) = cos(<em>ω</em><sub>0</sub><em>t</em>)<em>x</em>(<em>t</em>), and then demodulated by forming <em>z</em>(<em>t</em>) = <em>cos</em>(<em>ω</em><sub>0</sub><em>t</em>)<em>y</em>(<em>t</em>). Find and sketch <em>Z</em>(<em>ω</em>), assuming <em>ω</em><sub>0 </sub>is large.</li>

 <li>[10] A signal <em>x</em>(<em>t</em>) with spectrumrect is filtered by a system with frequency</li>

</ol>

response <em>H</em>(<em>ω</em>) = rect. The resulting signal is then multiplied by cos(8<em>πt</em>). Finally, that signal is passed through an integrator system, yielding a signal <em>y</em>(<em>t</em>). Find and sketch <em>Y </em>(<em>ω</em>).

<ol start="11">

 <li>Asynchronous modulation-demodulation requires the injection of the carrier signal so that the modulated signal is of the form <em>y</em>(<em>t</em>) = [<em>A </em>+ <em>x</em>(<em>t</em>)]cos(<em>ω<sub>c</sub>t </em>+ <em>θ<sub>c</sub></em>)</li>

</ol>

where <em>A </em>+ <em>x</em>(<em>t</em>) <em>&gt; </em>0 for all <em>t</em>. The presence of the carrier means that more transmitter power is required, representing an inefficiency.

<ul>

 <li>[4] Let <em>x</em>(<em>t</em>) = cos<em>ω<sub>M</sub>t </em>with <em>ω<sub>M </sub>&lt; ω<sub>c </sub></em>and <em>A</em>+<em>x</em>(<em>t</em>) <em>&gt; </em> For a periodic signal <em>y</em>(<em>t</em>) with period <em>T</em>, the average power over time is defined as <em>P<sub>y </sub></em>= (1<em>/T</em>)<sup>R</sup><em><sub>T </sub>y</em><sup>2</sup>(<em>t</em>)<em>dt</em>. Determine <em>P<sub>y </sub></em>for <em>y</em>(<em>t</em>) defined above. Express your answer as a function of the modulation index <em>m</em>, defined as the maximum absolute value of <em>x</em>(<em>t</em>) divided by <em>A</em>.</li>

 <li>[4] The efficiency of transmission of an amplitude-modulated signal is defined to be the ratio of the power in the sidebands (i.e., power of modulated signal that does not come from DC input) of the signal to the total power in the signal. With <em>x</em>(<em>t</em>) = cos<em>ω<sub>M</sub>t</em>, and with <em>ω<sub>M </sub>&lt; ω<sub>c </sub></em>and <em>A </em>+ <em>x</em>(<em>t</em>) <em>&gt; </em>0, determine and sketch the efficiency of the modulated signal as a function of the modulation index <em>m</em>.</li>

</ul>

<ol start="12">

 <li>The accurate demultiplexing-demodulation of radio and television signals is generally performed using a system called the superheterodyne receiver, which is equivalent to a tunable filter. The basic system is shown as below.

  <ul>

   <li>[5] The input signal <em>y</em>(<em>t</em>) consists of the superposition of many amplitude-modulated signals that have been multiplexed using frequency-division multiplexing, so that each signal occupies a different frequency channel. Let us consider one such channel that contains the amplitude-modulated signal <em>y</em><sub>1</sub>(<em>t</em>) = <em>x</em><sub>1</sub>(<em>t</em>)cos<em>ω<sub>c</sub>t</em>, with spectrum <em>Y</em><sub>1</sub>(<em>ω</em>) within [<em>ω<sub>c </sub></em>− <em>ω<sub>M</sub>,ω<sub>c </sub></em>+ <em>ω<sub>M</sub></em>] as depicted below. We want to demultiplex and demodulate <em>y</em><sub>1</sub>(<em>t</em>) to recover the modulating signal <em>x</em><sub>1</sub>(<em>t</em>), using the system in the figure. The coarse tunable filter has the spectrum <em>H</em><sub>1</sub>(<em>ω</em>). Determine the spectrum <em>Z</em>(<em>ω</em>) of the input signal to the fixed selective filter <em>H</em><sub>2</sub>(<em>jω</em>). Sketch and label <em>Z</em>(<em>ω</em>) for <em>ω &gt; </em></li>

   <li>[5] The fixed frequency-seletive filter is a bandpass type centered around the fixed frequency <em>ω<sub>f</sub></em>. We would like the output of the filter with spectrum <em>H</em><sub>2</sub>(<em>ω</em>) to be <em>r</em>(<em>t</em>) = <em>x</em><sub>1</sub>(<em>t</em>)cos<em>ω<sub>f</sub>t</em>. In terms of <em>ω<sub>c </sub></em>and <em>ω<sub>M</sub></em>, what constraint must <em>ω<sub>T </sub></em>satisfy to guarantee that an undistorted spectrum of <em>x</em><sub>1</sub>(<em>t</em>) is center around <em>ω </em>= <em>ω<sub>f</sub></em>?</li>

   <li>[5] What must <em>G</em>, <em>α</em>, and <em>β </em>be in the figure so that <em>r</em>(<em>t</em>) = <em>x</em><sub>1</sub>(<em>t</em>)cos<em>ω<sub>f</sub>t</em>.</li>

  </ul></li>

</ol>