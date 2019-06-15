JFLAGS = -g
JC = javac
.SUFFIXES: .java .class
.java.class:
	$(JC) $(JFLAGS) $*.java

CLASSES = \
	CSVLoader.java \
	Student.java 

default: classes

classes: $(CLASSES:.java=.class)

clean:
	$(RM) *class
