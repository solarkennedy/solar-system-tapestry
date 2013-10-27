all: sun.cst sun_out.gif

sun_out.gif:
	convert original.png -remap ../DMC/dmc.png sun_out.gif

sun.cst:
	xz -d -k sun.cst.xz

clean:
	rm sun_out.gif
	rm sun.cst

crosti:
	crosti sun.cst
