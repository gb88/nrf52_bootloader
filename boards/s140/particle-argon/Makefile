include ../Makefile.boards

CFLAGS += -DBOARD_CUSTOM

ASMFLAGS += -DBOARD_CUSTOM

ifeq ($(PBRICK_DEBUG), 1)
CFLAGS += -DNRF_LOG_BACKEND_UART_TX_PIN=6
ASMFLAGS += -DNRF_LOG_BACKEND_UART_TX_PIN=6
endif