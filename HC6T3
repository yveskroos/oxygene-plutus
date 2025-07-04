HC6T3 qui demande d'implémenter une fonction Haskell utilisant `foldr` pour calculer la somme des éléments d'une liste :


Somme avec "foldr"


-- Fonction qui calcule la somme avec foldr
sumList :: [Int] -> Int
sumList = foldr (+) 0

-- Fonction main pour exécuter un exemple
main :: IO ()
main = do
    let liste = [1, 2, 3, 4, 5]  -- Exemple de liste
    putStrLn ("La somme de la liste est " ++ show (sumList liste))


  Exécution

Enregistrez ce code dans "Main.hs" puis lancez :


ghc Main.hs -o sumlist && ./sumlist


Ou si tu utilises "Cabal" dans un projet :


cabal run
