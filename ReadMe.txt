- If you want to support S5 WOL, you have to find

	EXTRA_CFLAGS += -DRTL8152_S5_WOL

  in the Makefile. Then, remove the first character '#", if it exists.


- For Fedora, you may have to run the following command after installing the
  driver.

	# dracut -f

- For Ubuntu, you may have to run the following command after installing the
  driver.

	# sudo update-initramfs -u
