# .gitignore说明

### EWARM 必要组件

IAR环境工程中，下面这几个是不能加入到过滤，其他再额外生成的文件均可过滤

```bash
EWARM 必要组件
.
├── HK32F103.ewd
├── HK32F103.ewp
├── Project.eww
├── dlib_lock_glue.c
├── startup_stm32f103xe.s
├── stm32_lock.h
├── stm32f103xe_flash.icf
└── stm32f103xe_sram.icf
```

