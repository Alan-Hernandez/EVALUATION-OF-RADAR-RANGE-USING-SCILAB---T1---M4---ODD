# EVALUATION-OF-RADAR-RANGE-USING-SCILAB---T1---M4---ODD
## Aim
To calculate the maximum range of a radar system using the Radar Range Equation and verify the results through Scilab programming.

## Apparatus Required
1. **Software:** Scilab environment
2. **Hardware:** Personal Computer

---

## Theory
The Radar Range Equation is a fundamental formula used in radar system design to determine the maximum range at which a radar can detect a target. 

### Mathematical Representation
The maximum radar range $R_{\max}$ is given by:

$$R_{\max} = \left( \frac{P_t G_t G_r \lambda^2 \sigma}{(4\pi)^3 P_{\min}} \right)^{\frac{1}{4}}$$

Where:
* $R_{\max}$ : Maximum detectable range of the radar (m)
* $P_t$ : Transmitted power (W)
* $G_t$ : Gain of the transmitting antenna
* $G_r$ : Gain of the receiving antenna
* $\lambda$ : Wavelength of the radar signal (m), calculated as $\lambda = \frac{c}{f}$ (where $c = 3 \times 10^8 \text{ m/s}$)
* $\sigma$ : Radar cross-section of the target ($\text{m}^2$)
* $P_{\min}$ : Minimum detectable signal power of the receiver (W)

---

## Procedure / Algorithm
1. **Set Up the Scilab Environment:** Launch the Scilab workspace/console.
2. **Define Parameters:** Set values for transmitted power ($P_t$), antenna gains ($G_t, G_r$), frequency ($f$), radar cross section ($\sigma$), and minimum power ($P_{\min}$).
3. **Calculate Wavelength:** Convert signal frequency to wavelength using $\lambda = \frac{c}{f}$, where $c = 3 \times 10^8 \text{ m/s}$.
4. **Define Radar Range Equation:** Compute the numerator and denominator using Scilab's built-in math functions and `%pi`.
5. **Calculate Maximum Range:** Evaluate $R_{\max}$ by raising the ratio to the power of $0.25$ (1/4th power).
6. **Execute and Display Results:** Run the Scilab script (`.sce`) to display the maximum radar range in meters and kilometers.

---
## TABULATION 
<img width="1600" height="1010" alt="image" src="https://github.com/user-attachments/assets/4d5902ce-9de7-4a2c-9e1d-cc5c53b30254" />

## CODING 
<img width="1452" height="1600" alt="image" src="https://github.com/user-attachments/assets/5f3165bc-deee-412e-93bd-519b72902c37" />
<img width="1032" height="1600" alt="image" src="https://github.com/user-attachments/assets/292eaeed-183b-4703-a60b-e5bb345d54e1" />
<img width="1050" height="1600" alt="image" src="https://github.com/user-attachments/assets/e29988ca-252a-4a4c-85b6-12d776c58aef" />
<img width="1600" height="1550" alt="image" src="https://github.com/user-attachments/assets/a4876093-2f69-4ca9-905e-2ecea5aaedcd" />

## MODEL GRAPH
<img width="1755" height="848" alt="image" src="https://github.com/user-attachments/assets/b18ab1f8-bdbc-47d9-8c4d-b50f11a91751" />

## RESULT 
<img width="1600" height="880" alt="image" src="https://github.com/user-attachments/assets/79000d41-222e-4d29-a196-81244f872656" />

## MARK ALLOCATION 
<img width="1600" height="982" alt="image" src="https://github.com/user-attachments/assets/5ea2cb35-5518-4305-b2de-47f904ebb001" />



