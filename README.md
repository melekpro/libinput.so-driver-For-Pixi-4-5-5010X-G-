# libinput.so-driver-For-Pixi-4-5-5010X-G-
var_8= -8
arg_0=  0
; __unwind {
PUSH            {R0,R1,R4,LR}
ADD             R1, SP, #0x10+var_8
MOV             R4, R0
ADDS            R0, #0x54 ; this
STRD.W          R2, R3, [R1,#-8]!
BLX             _ZN7android10VectorImpl4pushEPKv ; android::VectorImpl::push(void const*)
LDR             R1, [SP,#0x10+arg_0] ; void *
ADD.W           R0, R4, #0x68 ; this
LDR             R2, [R4,#0x48] ; unsigned int
BLX             _ZN7android10VectorImpl11appendArrayEPKvj ; android::VectorImpl::appendArray(void const*,uint)
ADD             SP, SP, #8
POP             {R4,PC}
