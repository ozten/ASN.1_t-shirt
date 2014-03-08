# ASN.1 Fanboy T-Shirt

![](http://dl.dropbox.com/u/10060532/Screenshots/6XVh.png)

## Option 1 Boast Protocol in DER

(Not on the shirt)

    Boast ::= SEQUENCE {
      encoding IA5String,
      durationQuantity INTEGER,
      durationType IA5String
    }

    asn Boast ::= {
      encoding "ASN.1",
      durationQuantity 4,
      durationType "LIFE"
    }

(Shirt Tagline)

    30 10 80 05 41 53 4E 2E 31 81 01 04 82 04 4C 49 46 45


(Not on the shirt, explanation)

    Sequence
             Len (5)
                A  S  N  .  1
                                  Len (1)
                                      4
                                           Len (4)
                                              L  I  F  E

## Option 2

Alternative PrintablString "ANS.1 4 LIFE" in DER

    1341534E 2E312034 204C4946 45810104 82044C49 4645