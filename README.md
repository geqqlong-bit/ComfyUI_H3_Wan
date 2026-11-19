🎬 ComfyUI 1080p+ 视频生成工作站（MiniMax-H3 音画同出 + 社区 NSFW 版 Wan 2.2 + 自定义 LoRA）
本笔记专为 Google Colab (L4 / A100 + 高 RAM) 环境深度调优，开箱集成：

MiniMax-H3 (33B)：支持文生音视频 / 首尾帧图生音视频，搭载 FP8_scaled 主模型 + 全精度双 VAE + 3D 潜空间 1080p/2K 放大器（保留原生立体声效）。
Wan 2.2 社区 NSFW/Spicy 无限制版：搭载无审查编码器 NSFW-Wan-UMT5-XXL + Wan2.2-Remix NSFW（I2V v3.0 / T2V v2.0）或 Phr00t Rapid-Mega-AIO NSFW，完美兼容社区高/低噪自定义 LoRA。
通用真 1080p/2K 超分管线：内置 SeedVR2 Video Upscaler 单步扩散视频超分与 RIFE 视频丝滑补帧。
持久化云端资产：自动将生成的视频、工作流画布及私人 LoRA 文件夹映射至 Google Drive，断联不丢文件、无需重复下载 LoRA。
⚠️ 运行前必读：

算力建议：日常玩 Wan 2.2 NSFW + LoRA + 1080p 选 L4 GPU（高 RAM） 性价比最高；跑 MiniMax-H3 建议切 A100 GPU。
协议授权：若勾选下载 MiniMax-H3，请先登录你的 Hugging Face 账号并访问 Comfy-Org/MiniMax-H3 点击同意协议（Agree/Accept），否则 API 会报 401/403 权限错误。
