As I’ve been learning power electronics from Prof. Shabari Nath of the Indian Institute of Technology Guwahati on YouTube, one topic that stood out to me
was the difference between bipolar and unipolar PWM.

A key distinction between the two is how power is delivered. In bipolar PWM, the output switches directly between positive and negative voltage levels, effectively using
the input voltage in a simpler way. In contrast, unipolar PWM utilizes both positive and negative switching states more efficiently within the H-bridge configuration,
resulting in improved output performance.

From the LTSpice simulations below, we can observe these differences:

Bi-polar PWM:
![image alt](https://github.com/Gmm-000/Personal-Project/blob/c2f3a07276d223a57ed13e5b32030068a82b5994/LTSpice/Screenshot%202026-04-04%20212656.png)

Uni-polar PWM:
![image alt](https://github.com/Gmm-000/Personal-Project/blob/25f839be7301c9417a734d3c567e83b21dc626b9/LTSpice/Screenshot%202026-04-04%20215854.png)

Side-by-side comparison:
![image alt](https://github.com/Gmm-000/Personal-Project/blob/25f839be7301c9417a734d3c567e83b21dc626b9/LTSpice/Screenshot%202026-04-04%20220054.png)

From these results, we can see that unipolar PWM makes better use of the available input voltage range. Additionally, the output current appears higher compared to bipolar
PWM under similar conditions, indicating more effective power delivery.

In conclusion, unipolar PWM is generally preferred in applications where efficient use of the full input voltage is important, such as wireless power transfer (WPT) or
higher-voltage systems. Bipolar PWM, on the other hand, may still be suitable for simpler or lower-voltage applications where implementation complexity is a concern.
