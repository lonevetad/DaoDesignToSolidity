# DaoDesignToSolidity
Translator do a DAO designed (mostly in XML format) to its Solidity implementation


# To Compile the new grammar
type:
antlr4 -Dlanguage=Python3 -no-listener -visitor <GRAMMAR NAME>.g


# To Run
To run the script digesting the input file, like the example one, type:
python <script>.py <XML file>.xml
