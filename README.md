This is a fork of [Fannovel16's ComfyUI ControlNet Auxiliary Preprocessors](https://github.com/Fannovel16/comfyui_controlnet_aux) that removes the `svglib` requirement. `svglib` appears to be breaking deployments on ComfyDeploy because of a Cairo/CMake issue. Since users' ability to tweak the live machines is limited, `svglib` has been removed from here to prevent the deployment break.

If this issue is addressed upstream, I'll remove this fork and re-point our deployments there.

I can't tell if SVGLib is actually used, so maybe this is an improvement, or maybe it's breaking something that's not present in my workflows. Let me know if you find a better solution!
