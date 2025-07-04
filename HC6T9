HC6T9, qui demande d’implémenter une fonction qui applique une fonction donnée à chaque élément d’une liste (comme `map`) en utilisant la récursion.

 Implémentation récursive de map


-- Fonction récursive qui applique f à chaque élément de la liste
myMap :: (a -> b) -> [a] -> [b]
myMap _ []     = []
myMap f (x:xs) = f x : myMap f xs

-- Fonction main pour tester
main :: IO ()
main = do
    let liste = [1, 2, 3, 4, 5]
    let result = myMap (*2) liste  -- Multiplie chaque élément par 2
    putStrLn ("Résultat de myMap (*2) sur la liste : " ++ show result)


  Exécution

1. Enregistre le code dans Main.hs.
2. Compile et exécute :


ghc Main.hs -o mymap && ./mymap


Ou avec Cabal :


cabal run
