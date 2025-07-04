HC6T7, où tu dois implémenter une fonction Haskell récursive qui retourne la longueur d'une liste :

---

   Longueur d'une liste (version récursive)

```haskell
-- Fonction récursive qui calcule la longueur d'une liste
listLength :: [a] -> Int
listLength []     = 0
listLength (_:xs) = 1 + listLength xs

-- Fonction main pour tester
main :: IO ()
main = do
    let liste = [1, 3, 5, 7, 9]
    putStrLn ("La longueur de la liste est : " ++ show (listLength liste))


  Exécution

1. Enregistre le code dans `Main.hs`.
2. Puis exécute avec :


ghc Main.hs -o listlength && ./listlength


Ou avec Cabal :


cabal run
