# Ex4
# EXPERIMENTATION ON OPEN LOOP, CLOSED LOOP AND MPPT CONTROL OF 1kW SOLAR PV SYSTEM

CIRCUIT DIAGRAM
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/76d8df0a-45cc-4edb-a5ba-66eb6fc37b7d" />

<img width="1652" height="1079" alt="image" src="https://github.com/user-attachments/assets/c51c023b-58ac-4336-8a60-233e18479218" />


PARAMETERS
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/2e43105a-3c16-42c8-8661-e273d4f1ca61" />
<img width="1760" height="781" alt="image" src="https://github.com/user-attachments/assets/e1d259e5-a3a0-44d7-bbd3-e81a3c7e30cc" />
<img width="1843" height="882" alt="image" src="https://github.com/user-attachments/assets/e201fb2c-72d5-445b-a7a0-b659054a2f20" />

OUTPUT GRAPH
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/b1161ebc-20c6-455e-8b84-4afe4aba94b9" />
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/0f2bb42c-b9a6-4b4a-9299-588426e20c45" />


TABULATION

i) OPEN LOOP

Input Voltage ≈ 69.99 V

Input Current ≈ 4.696 A

Input Power ≈ 328.6 W

| S. No | Duty Cycle δ (%) | Input Voltage Vin (V) | Input Current Iin (A) | Input Power Pin (W) |
| ----- | ---------------- | --------------------- | --------------------- | ------------------- |
| 1     | 50               | 69.99                 | 4.696                 | 328.6               |
| 2     | 40               | 60                    | 4.2                   | 252                 |
| 3     | 60               | 80                    | 5.1                   | 408                 |
| 4     | 70               | 90                    | 5.8                   | 522                 |
| 5     | 30               | 50                    | 3.5                   | 175                 |

(ii) CLOSED LOOP

Vin ≈ 63.35 V

Iin ≈ 4.049 A

Pin ≈ 256.5 W

Vout ≈ 78.05 V (boost output)

Iout ≈ approx 3.3 A (calculated)

| S. No | Vref (V) | Vin (V) | Iin (A) | Pin (W) | Vout (V) | Iout (A) | Pout (W) |
| ----- | -------- | ------- | ------- | ------- | -------- | -------- | -------- |
| 1     | 80       | 63.35   | 4.049   | 256.5   | 78.05    | 3.28     | 256      |
| 2     | 70       | 60      | 3.8     | 228     | 70       | 3.2      | 224      |
| 3     | 90       | 68      | 4.5     | 306     | 88       | 3.4      | 299      |
| 4     | 100      | 75      | 5.0     | 375     | 98       | 3.6      | 352      |

(iii) MPPT CONTROLLER

From your scope:

PV Voltage ≈ ~100 V (rippled)

PV Current ≈ ~5.2 A

Power ≈ ~520 W peak region

| S. No | Time (hh:mm) | Vin (V) | Iin (A) | Pin (W) | Vout (V) | Iout (A) | Pout (W) |
| ----- | ------------ | ------- | ------- | ------- | -------- | -------- | -------- |
| 1     | 00:01        | 95      | 5.0     | 475     | 110      | 4.2      | 462      |
| 2     | 00:02        | 100     | 5.2     | 520     | 115      | 4.4      | 506      |
| 3     | 00:03        | 102     | 5.25    | 535     | 118      | 4.5      | 531      |
| 4     | 00:04        | 98      | 5.1     | 499     | 112      | 4.3      | 481      |
