# Zest_Core_STM32H743ZG
[Zest_Core_STM32H743ZG](https://gitlab.com/catie_6tron/zest-core-stm32h743zg-hardware)
custom target for Mbed OS.

## Usage
In your project root directory:

1.  Add the custom target to your project:

    ```shell
    mbed add https://gitlab.com/catie_6tron/zest-core-stm32h743zg.git
    ```

2. Enable the custom target by adding or overwriting the `custom_targets.json` at the
   root of the project:

    ```shell
    cp zest-core-stm32h743zg/custom_targets.json .
    ```

3. Compile for the custom target:

   ```shell
   mbed compile --target ZEST_CORE_STM32H743ZG
   ```
