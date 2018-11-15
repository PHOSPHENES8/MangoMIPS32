# MangoMIPS32
轻量级CPU软核，兼容MIPS32 release 1架构

**开发中，将在第一个正式发布版本中更新此文档**

## 开发进度：
已实现、未调试指令：
- BEQL/BNEL/BGTZL/BLEZL/BGEZL/BGEZALL/BLTZL/BLTZALL


已通过调试指令：
- SLL/SRL/SRA/SLLV/SRLV/SRAV
- SYNC/PREF/CACHE (作为空指令)
- AND/OR/XOR/NOR
- MOVZ/MOVN/MFHI/MFLO/MTHI/MTLO
- ANDI/ORI/XORI/LUI
- ADD/ADDU/SUB/SUBU/SLT/SLTU/CLO/CLZ
- ADDI/ADDIU/SLTI/SLTIU
- MUL/MULT/MULTU/MADD/MADDU/MSUB/MSUBU/DIV/DIVU
- J/JAL/JR/JALR
- BEQ/BNE/BGTZ/BLEZ/BGEZ/BGEZAL/BLTZ/BLTZAL
- LB/LBU/LH/LHU/LW/LWL/LWR/LL
- SB/SH/SW/SWL/SWR/SC
