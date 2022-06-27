#include <stdio.h>
#include "pico/stdlib.h"

int main(void) {
  gpio_init(25);
  gpio_set_dir(25,true);
  stdio_init_all();
  while (true) {
    gpio_put(25,false);
    sleep_ms(250);
    gpio_put(25,true);
    sleep_ms(250);
  }
}
