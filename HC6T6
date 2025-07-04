HC6T6, qui demande une fonction Haskell récursive pour vérifier si un élément donné existe dans une liste.

---

– Vérification de présence dans une liste


-- Fonction récursive qui vérifie si un élément est dans une liste
elementExists :: Eq a => a -> [a] -> Bool
elementExists _ [] = False
elementExists x (y:ys)
    | x == y    = True
    | otherwise = elementExists x ys

-- Fonction main pour tester
main :: IO ()
main = do
    let liste = [10, 20, 30, 40]
    let valeur = 30
    putStrLn ("L'élément " ++ show valeur ++ (if elementExists valeur liste then " est" else " n'est pas") ++ " dans la liste.")

---

  Exécution

1. Sauvegarde ce code dans "Main.hs".
2. Compile ou lance avec :


ghc Main.hs -o elementcheck && ./elementcheck

Ou avec Cabal :


cabal run
