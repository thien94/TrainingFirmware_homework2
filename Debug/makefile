################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./Functions.obj" \
"./SystemConfig.obj" \
"./main.obj" \
"./startup_ccs.obj" \
"./utils/cmdline.obj" \
"./utils/uartstdio.obj" \
"./utils/ustdlib.obj" \
"./drivers/buttons.obj" \
"./drivers/rgb.obj" \
"../tm4c123gh6pm.cmd" \
-l"libc.a" \
-l"C:/ti/TivaWare_C_Series-2.1.0.12573/examples/boards/ek-tm4c123gxl/qs-rgb/ccs/../../../../../driverlib/ccs/Debug/driverlib.lib" \
-l"C:/ti/TivaWare_C_Series-2.1.0.12573/examples/boards/ek-tm4c123gxl/qs-rgb/ccs/../../../../../usblib/ccs/Debug/usblib.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include utils/subdir_vars.mk
-include drivers/subdir_vars.mk
-include subdir_rules.mk
-include utils/subdir_rules.mk
-include drivers/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 
EXE_OUTPUTS += \
[TIVA][FW2]\ _STATE_MACHINE.out \

EXE_OUTPUTS__QUOTED += \
"[TIVA][FW2] _STATE_MACHINE.out" \

BIN_OUTPUTS += \
[TIVA][FW2]\ _STATE_MACHINE.hex \

BIN_OUTPUTS__QUOTED += \
"[TIVA][FW2] _STATE_MACHINE.hex" \


# All Target
all: [TIVA][FW2]\ _STATE_MACHINE.out

# Tool invocations
[TIVA][FW2]\ _STATE_MACHINE.out: $(OBJS) $(CMD_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: ARM Linker'
	"c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4/bin/armcl" -mv7M4 --code_state=16 --float_support=FPv4SPD16 --abi=eabi -me -O2 -g --gcc --define=ccs="ccs" --define=PART_TM4C123GH6PM --define=TARGET_IS_TM4C123_RB1 --define=UART_BUFFERED --display_error_number --diag_warning=225 --diag_wrap=off --gen_func_subsections=on --ual -z -m"qs-rgb_ccs.map" --heap_size=0 --stack_size=4096 -i"c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4/lib" -i"c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4/include" --reread_libs --warn_sections --display_error_number --diag_wrap=off --xml_link_info="[TIVA][FW2] _STATE_MACHINE_linkInfo.xml" --rom_model -o "[TIVA][FW2] _STATE_MACHINE.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '
	@$(MAKE) --no-print-directory post-build

[TIVA][FW2]\ _STATE_MACHINE.hex: $(EXE_OUTPUTS)
	@echo 'Invoking: ARM Hex Utility'
	"c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4/bin/armhex"  -o "[TIVA][FW2] _STATE_MACHINE.hex" $(EXE_OUTPUTS__QUOTED)
	@echo 'Finished building: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(EXE_OUTPUTS__QUOTED)$(BIN_OUTPUTS__QUOTED)
	-$(RM) "Functions.pp" "SystemConfig.pp" "main.pp" "startup_ccs.pp" "utils\cmdline.pp" "utils\uartstdio.pp" "utils\ustdlib.pp" "drivers\buttons.pp" "drivers\rgb.pp" 
	-$(RM) "Functions.obj" "SystemConfig.obj" "main.obj" "startup_ccs.obj" "utils\cmdline.obj" "utils\uartstdio.obj" "utils\ustdlib.obj" "drivers\buttons.obj" "drivers\rgb.obj" 
	-@echo 'Finished clean'
	-@echo ' '

post-build:
	-"c:/ti/ccsv6/utils/tiobj2bin/tiobj2bin" "[TIVA][FW2] _STATE_MACHINE.out" "[TIVA][FW2] _STATE_MACHINE.bin" "c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4/bin/armofd" "c:/ti/ccsv6/tools/compiler/ti-cgt-arm_5.2.4/bin/armhex" "c:/ti/ccsv6/utils/tiobj2bin/mkhex4bin"
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY: post-build

-include ../makefile.targets

