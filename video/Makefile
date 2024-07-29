INSTALL_DIR=$(HOME)/.local/bin


install:
	chmod +x run-on-cpu run-on-gpu
	ln -sr run-on-cpu $(INSTALL_DIR)/run-on-cpu
	ln -sr run-on-gpu $(INSTALL_DIR)/run-on-gpu

clean:
	rm $(INSTALL_DIR)/run-on-cpu
	rm $(INSTALL_DIR)/run-on-gpu

