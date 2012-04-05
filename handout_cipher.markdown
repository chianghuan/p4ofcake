#puzzle 1. Caesar
---

	Guvf zrffntr vf rapelcgrq va ebg 13. Lbhe nafjre vf svfupnxr.

solved. 
see also: ROT13

#puzzle 2. Substitution
---

	ISS NVVK DIPXYWA PIT AVSUY QIAOP PWZEHVNWIEDZ. CDYT ZVM LOTK HDY AVSMHOVT HV HDOA HYFH, ZVM COSS QY IQSY HV NYH HDY ITACYW, CDOPD OA IKMGQWIHY.

*hint: frequency analysis

solved.
see also: substitution cipher

#puzzle 3. Useful XOR
---

here is a piece of code:

	char key = xxx;
	char *plaintext = "xxxxxxxxxx...xxxxxxxxx";  // unknown plaintext
	for (int i = 0, _len = strlen(plaintext); i < _len; i++)
	{
		printf("%02x", (unsigned int)(key ^ plaintext[i]) % 256);
				
		// format %02x means that, the data is print in hexadecimal, pad with '0' when it's width < 2.
		// so the resulting output of %02x would be as: 02, 1f, bb, ...
	}

the ciphertext which the code prints is:

	f5c3d98cc1cdd58cd8ded58cd8c38cdfc3c0dac98cd8c4c5df8cdcdec3cec0c9c18cced58cd8c4c98ccadec9ddd9c9c2cfd58ccdc2cdc0d5dfc5df8cd5c3d98cc4cddac98cc0c9cddec2c9c8828ceed9d88ccd8cceded9d8c98ccac3decfc98ccdd8d8cdcfc78cced58cc9c2d9c1c9decdd8c5c2cb8ccdc0c08cdcc3dfdfc5cec0c98cc7c9d5df8cc5df8ccd8cdfc5c1dcc0c9de8cdbcdd58cc3d9d8828ce9c5d8c4c9de8cdbcdd58cd5c3d98ccfc4c3dfc9808ccfc3c2cbdecdd8d9c0cdd8c5c3c2df8d

revert it to the plaintext

*hint: exclusive or, xor cipher