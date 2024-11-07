java c
Project for Electronics 4
This assessment is 100% of the marks in Electronics 4. To pass you must achieve at least 40% overall.You should structure your answers in the form. of a typed and professionally presented report - you can use the questions numbers to refer to the section you are working on. You should include appropriate explanations of your method and mathematical working at each stage – up to 10% of your final mark may be deducted for poor presentation or explanations.
Any  information  not  contained  in  the  instructions  is  considered  to  be  an  “engineering decision” . You may make your own choices for these aspects.
Introduction to the problemIn this project you will design key parts of a fixed microwave link to transmit an audio signal between two points across a stretch of desert. The signal will be transmitted at very low power and at a frequency of your choice between 2 and 19 GHz. You are responsible for the receiver part of the design.The system will be amplitude modulated and the receiver front-end and demodulation will have a standard analogue configuration. The retrieved baseband audio signal will be digitised by an Analogue to Digital Converter (ADC) for further Digital Signal Processing (DSP).Some parts of this assignment require you to do your own research and seek-out information for yourself – you will be awarded marks for this. If you have referred to any books, papers or websites you should reference these in your answers. Show all your working.
Instructions
Part A: Mainly learning outcome 1 - high frequency circuitry.
1.   Sketch a suitable block-diagram for the  receiver section of the system. Explain (in a sentence or two) the purpose of each block in your diagram.                          (6 marks)
2.   Design a mast-head preamplifier for your system. A datasheet for a suitable transistor is supplied – however you may use another one if you wish (but, if you do, include its datasheet in your report). In particular, include:
a.    An   input  matching-circuit  design  (the  input  reflection  coefficient  of  the transistor is S11). A single stub, LC or ¼ wave match is suitable. Show all your working (for example Smith Charts) and a diagram with the lengths or values of your final design.           (4 marks)
b.   An  output  matching  circuit  design  (the  output  reflection  coefficient  is  S22). (4 marks)
c.   A suitable bias circuit for the transistor.                                                  (4 marks)
d.   A microstrip PCB layout for the amplifier. You may choose the substrate or PCB material.  Include  circuit  element   lengths  on  your   diagram  taking  εr    into account.                  (4 marks)
3.   Explain why your amplifier is best situated at the masthead (right next to the antenna) and   why   this   amplifier   is    particularly   important   in   terms   of   overall   system performance.             (2 marks)
4.   If you were to design such an amplifier in reality, you might have to take other factors into  account.  Explain  two  of  these  and  include  details  of  the  extra  calculations required (just state the formulae – there is no need to do the calculations). To answer this question, you will have to do some independent research, for example in the literature on microwave engineering. To give you a start answering the question you may wish to look up amplifier stability and S parameter design in a reference book.     (4 marks)
5.   Choose a suitable circuit for the first mixer in the system. If you wish, you may choose a packaged circuit, for example from a supplier like Minicircuits:Mini Circuits - Global Leader of RF and Microwave Components. Justify your choice of mixer.      (2 marks)
6.   Calculate the  noise figure  of your  circuit up to the output of your mixer. You may ignore noise added by the local oscillator, but include cabling, etc.               (8 marks)
7.   If the signal to noise ratio at the input to the system is 13 dB, calculate the signal to noise ratio at the output of the mixer – quote this in dB and as a simple ratio.   (2 marks)
Part B: Mainly learning outcome 2 - mixed signal代 写Project for Electronics 4SQL
代做程序编程语言 circuity.For this part, let us assume that a simple frequency synthesiser will be used in the system (it doesn’t matter if you used a fixed oscillator as part of the topology in part A – that was quite acceptable). This synthesiser will be used as the first local oscillator and its output will be mixed with the wanted signal to produce a first intermediate frequency (IF) of 50 MHz. The synthesiser will provide a small number of channels that can be used as alternatives should interference appear on the selected frequency.
8.   Draw a block diagram of a suitable frequency synthesiser and explain the purpose of each block and the overall operation of the synthesiser. You should provide any divide ratios required for the synthesiser to operate.      (8 marks)
9.   Describe the difference between a first and second order phase locked loop (PLL) – in terms of circuitry and performance (you may find a diagram useful here) . If you were to use a PLL asthe basis of this synthesiser, describe which type you would choose – justify your choice.         (3 marks)
10. Why do you think we might describe such a synthesiser as a “mixed signal” circuit. (1 mark)
11. Submit  your  answers  to  Tasks  1a  and  2b  from  the  notes  on  frequency  synthesis (section 3) for this question (calculation of PLL parameters).                           (7 marks)
12. Compare a PLL frequency synthesiser to a direct digital synthesis (DDS) synthesiser – outline an advantage and disadvantage of one of these compared to the other. You should include a diagram of the synthesiser you didn’t use in Q8.You don’thave togo into detail on the requirements for this particular application.                       (3 marks)
Part C: Mainly learning outcome 3 - digital signal processing.For this part of the project, we will assume that the audio signal has been successfully demodulated and is present at its original frequencies. It is now to be digitised and further processed using DSP. You may choose the nature of the audio signal itself – for example: high or low quality speech, broadcast or consumer quality music or any other baseband signal within (or close to) the audio spectrum.
13. Choose  the  specification  of  a  suitable  ADC  for  your  chosen  signal.  Both  voltage resolution and sampling frequency should be considered. Also outline the design of a suitable antialiasing filter for this (in terms of the type of filter, it’s cutoff and a suitable technology).                                                                                                                (4 marks)
14. How much extra noise will the ADC add to your system?                                  (2 marks)
15. Let us assume that the audio signal starts at 0 Hz but needs to be filtered at its upper limit to reduce high frequency noise. The filter should have a reasonably flat pass- band, but should also roll off by at least 30 dB within a few kHz of the signal edge.
Demonstrate the  design  process  for  a  FIR  low-pass  filter  by  working  through  the following steps:
a.   Choose and justify a suitable window for your filter.                            (2 marks)
b.   Based on this calculate the number of filter coefficients required.   (3 marks)
c.   Calculate (only!) the first four coefficients of your filter.                     (7 marks)
d.   Draw a sketch of how this filter might be implemented (you can do this with a block diagram and perhaps some pseudocode).                                    (2 marks)
16. Explain how the filter coefficients would be calculated in a large real design.      (1 mark)17. Explain with the aid of a diagram how this type of filter compares in structure to a IIR filter. Outline one advantage and one disadvantage of one compared to the other.   (4 marks)
18. If an engineer wished to examine the frequency content of the audio signal, explain an efficient way in which s/he might do so. Include and explain the algorithm for this (a diagram and explanation of how it works is sufficient for this).                  (3 marks)
Note: whole assessment marks add up to 90.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
