add_library(pico_pio_uart_tx_stdio pio_uart_tx_stdio.c)
pico_generate_pio_header(pico_pio_uart_tx_stdio ${CMAKE_CURRENT_LIST_DIR}/uart_tx.pio)
target_link_libraries(pico_pio_uart_tx_stdio PUBLIC pico_stdlib hardware_pio)
target_include_directories(pico_pio_uart_tx_stdio INTERFACE .)
