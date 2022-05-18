# MPS-from-3D-SIM
analysing SIM images to measure periodicity of MPS

I wrote this to analyse line profiles from images obtained using structured illumination microscopy (SIM) to analyse the periodicity of actin rings or other components of the membrane periodic skeleton (MPS). This will measure autocorrelation and distance between rings (peaks). To overcome noise caused by differences in intensity, it will also fit gaussians to individual peaks, and use a local normalisation algorithm (contributed by Guanglei Xiong (xgl99@mails.tsinghua.edu.cn) at Tsinghua University, Beijing, China). The script will analyse line profiles drawn across the MPS.
