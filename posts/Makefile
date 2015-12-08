# Produce PDFs from all Markdown files in a directory
# Lincoln Mullen | http://lincolnmullen.com | lincoln@lincolnmullen.com

# List files to be made by finding all *.md files and appending .html
SOURCES := $(patsubst %.md,%.html,$(wildcard *.md))

# The all rule makes all the PDF files listed
all : $(SOURCES)
	mv *.html ../cache
                        
# This generic rule accepts PDF targets with corresponding Markdown 
# source, and makes them using pandoc
%.html : %.md
	markdown $< >$@

# Remove all PDF outputs then build them again
rebuild : clean all
