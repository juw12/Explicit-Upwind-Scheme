# Upwind-Differencing-Scheme
The one dimensional wave propagation equation is given by 

<img width="219" alt="image" src="https://user-images.githubusercontent.com/73946469/126501812-364fb701-13a0-4ab8-8dda-539beab539f8.png">

<img width="220" alt="image" src="https://user-images.githubusercontent.com/73946469/126501825-11d2c7d8-2b01-4ef6-9911-5c7e782409b2.png">

where the initial conditions are to be stated by
<img width="364" alt="image" src="https://user-images.githubusercontent.com/73946469/126501764-b9d3242a-3e84-448f-8e05-e37ef561b794.png">
<img width="416" alt="image" src="https://user-images.githubusercontent.com/73946469/126501779-23f87ac2-0ac1-4707-821e-b18cd34eab37.png">

Dx is fixed to a value of 0.01, while u’s and dt’s values are given by 0.09 and 0.01

The solution by the first order backward differencing scheme accurate in first order in time and space is to be given by the equation below.

<img width="219" alt="image" src="https://user-images.githubusercontent.com/73946469/126502488-2993e020-7d56-417b-a5e1-f12470168e09.png">
where the scheme is stable for C ≤1, having an order of accuracy of [∆𝑡,∆𝑥].

