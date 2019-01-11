[![Hackage](https://img.shields.io/hackage/v/aeson-applicative.svg)](https://hackage.haskell.org/package/aeson-applicative)
[![Build Status](https://secure.travis-ci.org/louispan/aeson-applicative.png?branch=master)](http://travis-ci.org/louispan/aeson-applicative)

Aeson-like parsing 'Compose'd with an additional Applicative. ie.
`atoEncoding :: Applicative m => a -> m Encoding`
`aparseJSON :: Applicative m => Value -> Parser (m a)`
