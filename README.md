SpellChecker

SpellChecker is a stand-alone API, capable of operating on a block of word that may not be spelled correctly.

A SpellChecker carries out the following processes:
1. It scans the text and extracts the words contained in it.
2. It then compares each word with a known list of correctly spelled words (i.e. a dictionary).
3. Returns List of suggested words incase word entered is incorrect.

SpellChecker is highly optimized for faster and improved results and is completely written in JavaSE.

Following are the ways of using SpellChecker -

1. Import SpellChecker-2.1.jar in you Projects Build Path.
2. Use -cp 'path to .jar file' option to compile and execute you code.
3. Add a Maven dependency as :
   
    Add Repository Tag just below the defined properties
     <repositories>
		 <repository>
			<id>ad46829</id>
			<name>SpellChecker</name>
			<url>https://github.com/ad46829/SpellChecker/raw/master</url>
		 </repository>
	 </repositories>s>
    
    Add the SpellChecker dependency
        <dependency>
			<groupId>com.jsc.spellchecker</groupId>
			<artifactId>SpellChecker</artifactId>
			<version>2.1</version>**
		</dependency>
       

Thats it, you are done importing the API into your project.

Lets see how to use SpellChecker :

        List<?> answer = SpellChecker.checkWordSpelling(wordToCheck);

Yes!! thats it SpellChecker just requires a single line of code to do its work. Pretty easy haah! 💃.

Developer - Akash Dubey (akashdubey13093@gmail.com)
