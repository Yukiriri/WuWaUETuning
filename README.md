# WuWaUETuning
- 当前原生适配游戏版本：2.5.x

```
[/Script/Engine.RendererOverrideSettings]

; Res | 原生分辨率
r.ScreenPercentage=100
; r.Upscale.Quality=4

; AA | 抗锯齿
; r.TemporalAA.Upsampling=True
; r.TemporalAA.Algorithm=1
; r.Tonemapper.Sharpen=0.5
; r.PostProcessAAQuality=4

; Effects | 后期效果
r.Tonemapper.Quality=3
r.SceneColorFringeQuality=0
r.MotionBlur.TargetFPS=0

; Tone | 后期色调 （提高光源亮度上限）
r.KuroTonemapping=1
r.Color.Mid=0.5
r.Color.Max=1.25
r.DefaultFeature.AutoExposure.ExtendDefaultLuminanceRange=True
r.Kuro.AutoExposure=True
r.Kuro.EyeAdaptation.CustomValueMode=True
r.Kuro.EyeAdaptation.ExposureBiasOverride=0.0

; LOD | 细节层级
r.DetailMode=2
r.MaterialQualityLevel=1
r.KuroMaterialQualityLevel=1

; Shadow | 阴影
r.ShadowQuality=3
r.Shadow.RadiusThreshold=0.02
r.Shadow.CSM0ShadowPCFQuality=3
r.Shadow.CSM1ShadowPCFQuality=3
r.Shadow.CSM2ShadowPCFQuality=3
r.Shadow.PerObjShadowPCFQuality=3
r.Shadow.MinResolution=1024
r.Shadow.MaxCSMResolution=1024
r.Shadow.PerObjectResolutionMin=1024
r.Shadow.PerObjectResolutionMax=1024
r.Shadow.PerObjectShadowMapResolution=1024
r.Shadow.CacheMode3CacheUpdateIntervals=1,2,4,8,16,32,64,128

; Light | 光照
r.Kuro.LightFadeTime=5.0

```

# 性能优化推荐
- [WuWa-Configs](https://github.com/AlteriaX/WuWa-Configs)
