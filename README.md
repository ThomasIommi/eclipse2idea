# eclipse2idea

This projects takes an Eclipse Code Template and converts it to a IntelliJ Idea Live Template

## Installation

It's a simple Maven project: position to the root of the project and lunch the command `$ mvn install`.

In the target folder just created it should now be a .jar file named "eclipse2idea-{VERSION}-dep.jar".

## Usage

Lunch the command `$ java -jar eclipse2idea-{VERSION}-dep.jar -i {PATH-TO-INPUT} -o {PATH-TO-OUTPUT/FILE-NAME}`.

-o (output) is optional, default file name is "_output.xml_" in the folder where you are when you run the .jar.

Now you can copy and paste this Live Template in IntelliJ IDEA config folder, usually under: 
_/home/user/.IntelliJIdea2018.2/config/templates/_

## Credits

All credits for the original project goes to Alexander (__malkolm__) Krasnukhin.

I've found about this project here [https://code.google.com/archive/p/eclipse2idea/](), but it seems not to be available
anymore, since the Google Code service was shut down in 2015.
I've anyway found references to the original project by other people that have already cloned it and shared it on GitHub before me.

## License

Back in the Google Code Archive it was labeled under ___Apache License 2.0___.

