# HI, это не официальный гайд по настройке окружения для вашего любимого assembler :)

# 1. Для Linux

	PS Вот конвеер если не хотите копировать, можно будет перейти стразу на шаг 1.1.1: sudo apt-get update && sudo apt-get install dosemu wget unzip && cd && wget https://github.com/Elderly-AI/Dosemu/archive/master.zip && unzip master.zip && rm -rf master.zip

	1.0.0 открываем терминал
	1.0.1 sudo apt-get update 						// делаем update системы
	1.0.2 sudo apt-get install dosemu 					// ставим dosemu
	1.0.3 sudo apt-get install wget						// wget для закачки
	1.0.4 sudo apt-get install unzip					// unzip для раззиповки

	1.0.3 cd 								// переходим в домашний каталог
	1.0.3 wget https://github.com/Elderly-AI/Dosemu/archive/master.zip 	// качаем каталог
	1.0.4 unzip master.zip							// разархивируем
	1.0.5 rm -rf master.zip							// удаляем архив

	1.1.1 dosemu 								// запускаем эмулятор
	1.1.2 D: 								// переходим в домашний каталог (диск D)
	1.1.3 cd Dosemu-master 							// переходим в папочку Dosemu-master
	1.1.4 edit your-progtam.asm						// текстовый редактор
	1.1.5 utils\tasm.exe your-progtam.asm					// компилятор tasm
	1.1.6 utils\tlink.exe your-progtam.obj					// линковщие tlink
	1.1.7 utils\td\td.exe your-progtam.exe					// ваш любимый turbo debugger

# 2. Для windows и Mac

	1.0. Качаем DosBox https://sourceforge.net/projects/dosbox/
	1.1. качаем архивчик https://github.com/Elderly-AI/Dosemu/archive/master.zip
	1.2. распаковываем архивчик и запоминаем до него путь
	1.3. запускаем DosBox
	1.4. mount C путь-до-вашего-распакованного-архива			// Монтируем диск
	1.5. C:
	
	2.0. utils\edit.com							// текстовый редактор можно и просто через txt
	2.1. utils\tlink.exe your-progtam.obj					// линковщие tlink
	2.2. utils\td\td.exe your-progtam.exe					// ваш любимый turbo debugger
