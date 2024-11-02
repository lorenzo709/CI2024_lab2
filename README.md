The 2 algorithm i used for the TPS problem are:
- Brute_force
- Simulated_annealing

## Brute force

It's a simple and un-optimize algorithm that should return always the best route possible, since it tests all the possible combinations

|Country|Lenght best path (Km)|steps|
|---|---|---|
|CHINA|62850.47475129334|263175|
|US|49349.8721920727|52975|
|ITALY|5097.201397584548|1035|
|RUSSIA|42890.38555683937|13861|
|VANUATU|1475.528091104531|28|

## Simulated Annealing

I have used two forms of mutation.

The first is insert mutation as seen in class, the second is also insert mutation but i've tried to add to it the `temperature` value.

Hovewer, when i try to use the mutation with temperature in it, the result is always worst than the normal one.

I definitely implemented it badly, but i'm not sure how can i change it. I hope someone in the review can help me.

### normal Insert mutation

|Country|Lenght best path (Km)|steps|
|---|---|---|
|CHINA|167883.78 km|172494|
|US|74328.19 km|166842|
|ITALY|4685.04 km|90000|
|RUSSIA|48629.62 km|499999|
|VANUATU|1345.54 km|10000|

### temperature Insert mutation

|Country|Lenght best path (Km)|steps|
|---|---|---|
|CHINA|251474.76|160000|
|ITALY|8401.88|20000|
|RUSSIA|80262.19|60000|
|US|123120.52|90000|
|VANUATU|1345.54|10000|

NOTE: if you have to run the code locally please change the path to the files CVS.

I worked with: ALESSANDRO CARLONE s326994
