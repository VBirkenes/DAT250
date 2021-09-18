# Installation: MongoDB Database

I used SHA-256 to verify the MongoDB package. Second to last line says OK: 
<img width="874" alt="image" src="https://user-images.githubusercontent.com/50453041/133812515-49b49ae0-04e7-4869-a732-f4187d1886a3.png">

I used Homebrew to install MongoDB and encountered no technical problems.

# Experiment 1: MongoDB CRUD operations

### Insert:

<img width="380" alt="image" src="https://user-images.githubusercontent.com/50453041/133889114-2b5e91a1-4553-460a-94b5-c9d21c88510e.png">

### Query:

<img width="380" alt="image" src="https://user-images.githubusercontent.com/50453041/133889334-44d6314b-6dec-4628-9c6e-f46bb0588846.png">

### Update:

<img width="679" alt="image" src="https://user-images.githubusercontent.com/50453041/133889491-3e59a905-7202-4805-950b-a72df82e0baf.png">

### Remove:

<img width="500" alt="image" src="https://user-images.githubusercontent.com/50453041/133889586-d62a8cf2-2dee-4aef-b17d-7d09d2518df2.png">

### Bulk-write:


<img width="724" alt="image" src="https://user-images.githubusercontent.com/50453041/133889737-6173c128-facb-450e-af45-06079e29ec0b.png">


# Experiment 2: Aggregation

### Example map-reduce:

<img width="392" alt="image" src="https://user-images.githubusercontent.com/50453041/133890791-04d1f79d-79cb-436d-be0f-b6e2c68cb80f.png">

### Own function:

I thought it could be useful to know how much money the shop makes in a day. 
Approach:

<img width="409" alt="image" src="https://user-images.githubusercontent.com/50453041/133891649-f62a7b05-68fc-4e7b-8f9b-e96514867ff6.png">

<img width="273" alt="image" src="https://user-images.githubusercontent.com/50453041/133891660-ceb496e5-f2fc-4e1c-b88a-b2bf02986871.png">

Result:

<img width="432" alt="image" src="https://user-images.githubusercontent.com/50453041/133891678-6264aed4-6e40-4c46-97aa-f78d42cda581.png">

As we can see from the result the shop makes much more some days than others. This could of course be caused by a small sample size, but it could be worth keeping track over a longer period of time.

### Pending issues

None
