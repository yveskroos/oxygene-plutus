HC6T5, qui consiste à implémenter une **fonction récursive** pour inverser une liste en Haskell :


  Inversion récursive d'une liste

-- Fonction récursive qui inverse une liste
reverseList :: [a] -> [a]
reverseList []     = []
reverseList (x:xs) = reverseList xs ++ [x]

-- Fonction main pour tester
main :: IO ()
main = do
    let liste = [1, 2, 3, 4, 5]
    putStrLn ("Liste d'origine : " ++ show liste)
    putStrLn ("Liste inversée  : " ++ show (reverseList liste))


  Pour exécuter

1. Enregistre ce code dans "Main.hs".
2. Compile et exécute avec :


ghc Main.hs -o reverselist && ./reverselist


Ou avec Cabal :


cabal run
