Feladatok: névterek, túlterhelés
--------------------------------

1. Készíts egy `utils` névteret és implementálj benne egy `print` nevű függvényt, amely kiírja a standard output-ra, hogí "Hello World"
Hívd meg ezt a függvényt a globális névtérbei `main` függvényből.

2. A `util` namespace álljon két belső namespace-ből: `math` és `print`. A
`util::math` névtérbe írjál egy `factorial` nevű függvényt, ami visszaadja a
paraméterként kapott egész szám faktoriálisát. A `util::print`-be írjál egy
`demo` nevű függvényt, ami az előző függvény segítségével kiírja a
paraméterként kapott egész érték faktoriálisát. A globális `main`-ből hívd
meg a `util::print::demo` függvényt.

3. Definiálj két `min` függvényt a `util::math` névtérbe eltérő paraméterezéssel:
az egyik két `int`-et várjon paraméterként és adja vissza a kisebbet, a
másik egy `std::vector<int>`-et vár paraméterként és a vector legkisebb
elemét adja vissza.
