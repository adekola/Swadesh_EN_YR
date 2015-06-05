# Swadesh_EN_YR
Repository for a language translation utility written in Shell programming to translate from English to Yoruba using the vocabulary of Swadesh lists for English and Yoruba 

To use this utility, simply clone the repository into your system.
This requires that you have git installed. 
If you don't, install using this command
`yum install git `
OR
`sudo apt-get install git`

Once git is installed, you can then run
`git clone https://github.com/adekola/Swadesh_EN_YR.git`
to clone the reporsitory

After cloning, run `cd Swadesh_EN_YR` to enter into the utility's directory

Once in, ensure the two scripts have executable permissions by running
`chmod 777 translate tranlate_gui`

The terminal version of the utility expects the word to be translated as the first parameter, like so:
`./translate <word>`

Thus, a sample run of the terminal version of the utility will be:
`./translate father`

As for the GUI version, simply run `./translate_gui` which will bring up a simple GUI that expects a word to be translated


Localisation into Yoruba is yet to be implemented given the requirement for locales within the user's environment which currently doesn't include a locale for the Yoruba language.

Bugs can be reported to adekola.m.adebayo@gmail.com



