HC6T4, qui demande une fonction Haskell utilisant `foldl` pour calculer le **produit des éléments d’une liste :


Produit avec "foldl"

-- Fonction qui calcule le produit avec foldl
productList :: [Int] -> Int
productList = foldl (*) 1

-- Fonction main pour exécuter un exemple
main :: IO ()
main = do
    let liste = [1, 2, 3, 4, 5]  -- Exemple de liste
    putStrLn ("Le produit de la liste est " ++ show (productList liste))


  Exécution

#### Sauvegarde le code dans `Main.hs` puis exécute :

ghc Main.hs -o productlist && ./productlist

  Ou avec Cabal :


cabal run
