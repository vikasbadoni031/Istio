istioctl install --set meshConfig.outboundTrafficPolicy.mode=REGISTRY_ONLY #or ALLOW_ANY (by default its allow any)
https://istio.io/latest/docs/tasks/traffic-management/egress/egress-control/
