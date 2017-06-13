TARGET := application
BUILD := build

all: build

show: build
	open $(BUILD)/$(TARGET).pdf

build: $(TARGET).tex
	mkdir -p $(BUILD)
	xelatex -aux-directory=$(BUILD) -output-directory=$(BUILD) $< 