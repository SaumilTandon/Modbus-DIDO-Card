################################################################################
# Automatically-generated file. Do not edit!
# Toolchain: GNU Tools for STM32 (12.3.rel1)
################################################################################

-include ../makefile.init

RM := rm -rf

# All of the sources participating in the build are defined here
-include sources.mk
<<<<<<< HEAD
-include Drivers/STM32L0xx_HAL_Driver/Src/subdir.mk
=======
-include Drivers/STM32F0xx_HAL_Driver/Src/subdir.mk
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c
-include Core/Startup/subdir.mk
-include Core/Src/subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
endif

-include ../makefile.defs

OPTIONAL_TOOL_DEPS := \
$(wildcard ../makefile.defs) \
$(wildcard ../makefile.init) \
$(wildcard ../makefile.targets) \


<<<<<<< HEAD
BUILD_ARTIFACT_NAME := allinone-nucleo-l010rb
=======
BUILD_ARTIFACT_NAME := stm32MCU_fo30k6t6
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c
BUILD_ARTIFACT_EXTENSION := elf
BUILD_ARTIFACT_PREFIX :=
BUILD_ARTIFACT := $(BUILD_ARTIFACT_PREFIX)$(BUILD_ARTIFACT_NAME)$(if $(BUILD_ARTIFACT_EXTENSION),.$(BUILD_ARTIFACT_EXTENSION),)

# Add inputs and outputs from these tool invocations to the build variables 
EXECUTABLES += \
<<<<<<< HEAD
allinone-nucleo-l010rb.elf \

MAP_FILES += \
allinone-nucleo-l010rb.map \
=======
stm32MCU_fo30k6t6.elf \

MAP_FILES += \
stm32MCU_fo30k6t6.map \
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c

SIZE_OUTPUT += \
default.size.stdout \

OBJDUMP_LIST += \
<<<<<<< HEAD
allinone-nucleo-l010rb.list \
=======
stm32MCU_fo30k6t6.list \
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c


# All Target
all: main-build

# Main-build Target
<<<<<<< HEAD
main-build: allinone-nucleo-l010rb.elf secondary-outputs

# Tool invocations
allinone-nucleo-l010rb.elf allinone-nucleo-l010rb.map: $(OBJS) $(USER_OBJS) D:\allinone-nucleo-l010rb\STM32L010RBTX_FLASH.ld makefile objects.list $(OPTIONAL_TOOL_DEPS)
	arm-none-eabi-gcc -o "allinone-nucleo-l010rb.elf" @"objects.list" $(USER_OBJS) $(LIBS) -mcpu=cortex-m0plus -T"D:\allinone-nucleo-l010rb\STM32L010RBTX_FLASH.ld" --specs=nosys.specs -Wl,-Map="allinone-nucleo-l010rb.map" -Wl,--gc-sections -static --specs=nano.specs -mfloat-abi=soft -mthumb -Wl,--start-group -lc -lm -Wl,--end-group
=======
main-build: stm32MCU_fo30k6t6.elf secondary-outputs

# Tool invocations
stm32MCU_fo30k6t6.elf stm32MCU_fo30k6t6.map: $(OBJS) $(USER_OBJS) D:\stm32MCU_fo30k6t6\STM32F030K6TX_FLASH.ld makefile objects.list $(OPTIONAL_TOOL_DEPS)
	arm-none-eabi-gcc -o "stm32MCU_fo30k6t6.elf" @"objects.list" $(USER_OBJS) $(LIBS) -mcpu=cortex-m0 -T"D:\stm32MCU_fo30k6t6\STM32F030K6TX_FLASH.ld" --specs=nosys.specs -Wl,-Map="stm32MCU_fo30k6t6.map" -Wl,--gc-sections -static --specs=nano.specs -mfloat-abi=soft -mthumb -Wl,--start-group -lc -lm -Wl,--end-group
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c
	@echo 'Finished building target: $@'
	@echo ' '

default.size.stdout: $(EXECUTABLES) makefile objects.list $(OPTIONAL_TOOL_DEPS)
	arm-none-eabi-size  $(EXECUTABLES)
	@echo 'Finished building: $@'
	@echo ' '

<<<<<<< HEAD
allinone-nucleo-l010rb.list: $(EXECUTABLES) makefile objects.list $(OPTIONAL_TOOL_DEPS)
	arm-none-eabi-objdump -h -S $(EXECUTABLES) > "allinone-nucleo-l010rb.list"
=======
stm32MCU_fo30k6t6.list: $(EXECUTABLES) makefile objects.list $(OPTIONAL_TOOL_DEPS)
	arm-none-eabi-objdump -h -S $(EXECUTABLES) > "stm32MCU_fo30k6t6.list"
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
<<<<<<< HEAD
	-$(RM) allinone-nucleo-l010rb.elf allinone-nucleo-l010rb.list allinone-nucleo-l010rb.map default.size.stdout
=======
	-$(RM) default.size.stdout stm32MCU_fo30k6t6.elf stm32MCU_fo30k6t6.list stm32MCU_fo30k6t6.map
>>>>>>> 63ea5bca8f7a8eee393567cd996e9d27f876452c
	-@echo ' '

secondary-outputs: $(SIZE_OUTPUT) $(OBJDUMP_LIST)

fail-specified-linker-script-missing:
	@echo 'Error: Cannot find the specified linker script. Check the linker settings in the build configuration.'
	@exit 2

warn-no-linker-script-specified:
	@echo 'Warning: No linker script specified. Check the linker settings in the build configuration.'

.PHONY: all clean dependents main-build fail-specified-linker-script-missing warn-no-linker-script-specified

-include ../makefile.targets
