HC6T2, c’est-à-dire une fonction récursive en Haskell qui calcule le nième nombre de Fibonacci, avec une fonction "main" pour tester :


Code Haskell – Fibonacci récursif

-- Définition de la fonction fibonacci
fibonacci :: Integer -> Integer
fibonacci 0 = 0
fibonacci 1 = 1
fibonacci n = fibonacci (n - 1) + fibonacci (n - 2)

-- Fonction main pour exécuter un exemple
main :: IO ()
main = do
    let n = 10  -- Tu peux changer cette valeur pour tester d'autres positions
    putStrLn ("Le " ++ show n ++ "e nombre de Fibonacci est " ++ show (fibonacci n))

  
  📌 Pour exécuter

1. Enregistre ce code dans un fichier "Main.hs".
2. Ensuite, exécute-le comme ceci :

  Avec GHC :


ghc Main.hs -o fibonacci && ./fibonacci


  Ou avec Cabal :

cabal run
