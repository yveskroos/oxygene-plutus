implémenter une fonction récursive pour calculer la factorielle d’un nombre en Haskell, et l’exécuter avec un exemple :

Code Haskell pour la factorielle récursive

-- Définition de la fonction factorielle
factorial :: Integer -> Integer
factorial 0 = 1
factorial n = n * factorial (n - 1)

-- Fonction main pour exécuter un exemple
main :: IO ()
main = do
    let number = 5  -- Change ce nombre si tu veux tester une autre valeur
    putStrLn ("La factorielle de " ++ show number ++ " est " ++ show (factorial number))


   Instructions pour l’exécuter

1. Sauvegarde ce code dans un fichier "Main.hs".
2. Compile ou exécute avec GHC ou Cabal :

  Avec GHC :

ghc Main.hs -o factorial && ./factorial

#### Avec Cabal (si tu utilises un projet Cabal) :

Assure-toi que ce fichier est bien listé comme "Main.hs", et que le "main" est bien configuré dans ton ".cabal".

cabal run


