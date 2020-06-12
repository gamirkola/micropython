ESPIDF ?= /media/mirko/dati/fisso_ufficio/progettini/esp/esp-idf
BOARD ?= GENERIC
PORT ?= /dev/ttyUSB0
FLASH_MODE ?= dio
FLASH_SIZE ?= 8MB
DIR ?= /media/mirko/dati/fisso_ufficio/progettini/esp
#CROSS_COMPILE ?= xtensa-esp32-elf-

include Makefile

upload:
	cp $(DIR)/frozen/* ./modules
	make erase
	make deploy