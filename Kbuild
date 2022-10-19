ifeq ($(CONFIG_ARCH_KALAMA), y)
dtbo-y += kalama-audio.dtbo \
                 kalama-audio-cdp.dtbo \
                 kalama-audio-cdp-nfc.dtbo \
                 kalama-audio-wsa883x-cdp.dtbo \
                 kalama-audio-mtp.dtbo \
                 kalama-audio-mtp-nfc.dtbo \
                 kalama-audio-qrd.dtbo \
                 kalama-audio-atp.dtbo \
                 kalama-audio-rcm.dtbo \
                 kalama-audio-rumi.dtbo \
                 kalama-audio-hdk.dtbo \
                 kalama-sg-audio-hhg.dtbo
endif

ifeq ($(CONFIG_ARCH_SA8155), y)
dtbo-y +=  sa8155-audio.dtbo
endif

ifeq ($(CONFIG_QTI_QUIN_GVM), y)
dtbo-y +=  sa8155-vm-audio.dtbo
endif

ifeq ($(CONFIG_ARCH_LEMANS), y)
dtbo-y +=  lemans-audio.dtbo
endif

ifeq ($(CONFIG_ARCH_KHAJE), y)
dtbo-y += khaje-audio.dtbo \
		khaje-audio-idp.dtbo \
		khaje-audio-qrd.dtbo \
		khaje-audio-qrd-hvdcp3p5.dtbo \
		khaje-audio-idp-nopmi.dtbo \
		khaje-audio-idp-90hz.dtbo \
                khajeg-audio-idp.dtbo \
                khajeg-audio-idp-90hz.dtbo \
		khajeg-audio-qrd.dtbo \
		khajeg-audio-qrd-hvdcp3p5.dtbo \
		khaje-audio-qrd-nopmi.dtbo \
		khajeg-audio-qrd-nopmi.dtbo \
		khaje-audio-atp.dtbo \
		khaje-audio-idp-pm8010.dtbo \
		khaje-audio-idp-usbc.dtbo \
		khaje-nowcd.dtbo
endif

ifeq ($(CONFIG_ARCH_SDXPINN), y)
	ifeq ($(TARGET_SUPPORT), sa525m)
		dtbo-y += sa525m-audio.dtbo
	else
		dtbo-y +=  sdxpinn-audio.dtbo
	endif
endif

ifeq ($(TARGET_SUPPORT), sa410m)
dtbo-y += sa410m-audio-idp.dtbo
endif

 always-y    := $(dtb-y) $(dtbo-y)
 subdir-y    := $(dts-dirs)
 clean-files    := *.dtb *.dtbo
