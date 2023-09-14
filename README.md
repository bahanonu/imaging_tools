# Imaging analysis tools
A table containing imaging analysis tools for biology and neuroscience, with a focus on calcium imaging.

Created by <a href='https://bahanonu.com' target='_blank'>Biafra Ahanonu, PhD</a> (<a href='https://www.hhmi.org/scientists/biafra-ahanonu' target='_blank'>HHMI Hanna Gray Fellow</a>, <a href='https://basbaumlab.ucsf.edu/people/' target='_blank'>Basbaum Lab</a>, UCSF).

<p align="center">
  <a href="https://user-images.githubusercontent.com/5241605/94530890-9c3db280-01f0-11eb-99f0-e977f5edb304.gif">
    <img src="https://user-images.githubusercontent.com/5241605/94530890-9c3db280-01f0-11eb-99f0-e977f5edb304.gif" align="center" title="ciapkgMovie" alt="ciapkgMovie" width="60%" style="margin-left:auto;margin-right:auto;display:block;margin-bottom: 1%;">
  </a>
    <p align="center">Calcium imaging analysis with CIAtah (https://github.com/bahanonu/ciatah).</strong>
    </p>
</p>

The table can also be found at:
- https://bahanonu.com/brain/imaging_tools/
- https://bahanonu.com/syscarut/articles/233/

_Notes_:
- I use _cell extraction_ to refer to algorithms that perform cell segmentation and extract neural activity traces.
- In cases where the publication did not explicitly give the algorithm a name, made one based on the underlying method used.
- This table includes algorithms that simultaneously extract cell images/contours and reconstruct cell activity traces along with ones mainly focused on determining one or the other.
- Several calcium imaging related packages have also been included along with algorithms dealing with post-hoc handling of data or cell activity traces.
- Future versions of the repository will include table file (e.g. CSV) and basic LaTeX code so others can import or modify the table more easily going forward.
- Depending on monitor size and browser, scroll horizontally to see right-most table columns (e.g. websites/URLs).
- Any additional papers or algorithms that should be added or suggested updates to the table, leave a <a href='https://bahanonu.com/syscarut/articles/226/' target='_blank'>comment on the associated blog post</a> or open an issue on the GitHub page, I want to make sure everyone’s brilliant work is acknowledged!

<strong>
<figcaption class="caption" ><span class="id">Table 1:</span><span  
class="content">Ca<sup class="textsuperscript"><span 
class="rm-lmr-10x-x-109">2+</span></sup> imaging cell extraction and trace reconstruction algorithms</span></figcaption></strong><!--tex4ht:label?: x1-1012r -->
                                                                          

                                                                          
<div class="tabular"> <table id="TBL-1" class="tabular"><colgroup id="TBL-1-1g"><col 
id="TBL-1-1" /></colgroup><colgroup id="TBL-1-2g"><col 
id="TBL-1-2" /></colgroup><colgroup id="TBL-1-3g"><col 
id="TBL-1-3" /></colgroup><colgroup id="TBL-1-4g"><col 
id="TBL-1-4" /></colgroup><colgroup id="TBL-1-5g"><col 
id="TBL-1-5" /></colgroup><colgroup id="TBL-1-6g"><col 
id="TBL-1-6" /></colgroup><tr 
class="hline"><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td></tr><tr  
 style="vertical-align:baseline;" id="TBL-1-1-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-1-1"  
class="td11"># </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-1-2"  
class="td11">Method                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-1-3"  
class="td11">Year</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-1-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-1-5"  
class="td11">Notes/Code                                                                                                                                                                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-1-6"  
class="td11">Citation                                                                               </td>
</tr><tr 
class="hline"><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td></tr><tr  
 style="vertical-align:baseline;" id="TBL-1-2-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-2-1"  
class="td11">1   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-2-2"  
class="td11">PhaseCorrelation           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-2-3"  
class="td11">1996</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-2-4"  
class="td11">Motion correction.       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-2-5"  
class="td11">•  Phase correlation for motion correction, to include translation, rotation, and scale-invariance.                                                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-2-6"  
class="td11"><a 
href="#Xreddy1996fft">Reddy and Chatterji</a> <a 
href="#Xreddy1996fft">1996</a>                                                       </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-3-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-3-1"  
class="td11">2   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-3-2"  
class="td11">Turboreg                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-3-3"  
class="td11">1998</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-3-4"  
class="td11">Motion correction.       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-3-5"  
class="td11">•  Motion correction.<br 
class="newline" />•  <a href='http://bigwww.epfl.ch/thevenaz/turboreg/' target='_blank'>http://bigwww.epfl.ch/thevenaz/turboreg/</a><a 
 id="dx1-1014"></a>                                                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-3-6"  
class="td11"><a 
href="#Xthevenaz1998pyramid">Thevenaz et al.</a> <a 
href="#Xthevenaz1998pyramid">1998</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-4-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-4-1"  
class="td11">3   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-4-2"  
class="td11">subPixelPhase               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-4-3"  
class="td11">2002</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-4-4"  
class="td11">Motion correction.       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-4-5"  
class="td11">•  Closed-form solution to subpixel translation estimation using phase correlation.                                                                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-4-6"  
class="td11"><a 
href="#Xforoosh2002extension">Foroosh et al.</a> <a 
href="#Xforoosh2002extension">2002</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-5-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-5-1"  
class="td11">4   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-5-2"  
class="td11">ROI                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-5-3"  
class="td11">2005</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-5-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-5-5"  
class="td11">•  Matrix multiplication; in some methods neuropil/background subtraction implemented.                                                                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-5-6"  
class="td11"><a 
href="#XKerr2005">Kerr et al.</a> <a 
href="#XKerr2005">2005</a>; <a 
href="#XKuchibhotla2014">Kuchibhotla et al.</a> <a 
href="#XKuchibhotla2014">2014</a>; <a 
href="#XPeron2015">Peron et al.</a> <a 
href="#XPeron2015">2015</a>        </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-6-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-6-1"  
class="td11">5   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-6-2"  
class="td11">CellProfiler                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-6-3"  
class="td11">2006</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-6-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-6-5"  
class="td11">•  Multi-algorithm pipeline for cell segmentation.<br 
class="newline" />•  <a href='https://cellprofiler.org' target='_blank'>https://cellprofiler.org</a><a 
 id="dx1-1015"></a>                                                                                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-6-6"  
class="td11"><a 
href="#Xcarpenter2006cellprofiler">Carpenter et al.</a> <a 
href="#Xcarpenter2006cellprofiler">2006</a>; <a 
href="#Xmcquin2018cellprofiler">McQuin et al.</a> <a 
href="#Xmcquin2018cellprofiler">2018</a>; <a 
href="#Xlamprecht2007cellprofiler">Lamprecht et al.</a> <a 
href="#Xlamprecht2007cellprofiler">2007</a></td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-7-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-7-1"  
class="td11">6   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-7-2"  
class="td11">PCA-ICA                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-7-3"  
class="td11">2009</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-7-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-7-5"  
class="td11">•  Cell extraction using principal component analysis (PCA) followed by independent component analysis (ICA).                                                                                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-7-6"  
class="td11"><a 
href="#Xmukamel2009automated">Mukamel et al.</a> <a 
href="#Xmukamel2009automated">2009</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-8-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-8-1"  
class="td11">7   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-8-2"  
class="td11">ANTs                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-8-3"  
class="td11">2009</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-8-4"  
class="td11">Image analysis            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-8-5"  
class="td11">•  Suite of tools for registering and analyzing imaging data.<br 
class="newline" />•  <a href='http://stnava.github.io/ANTs/' target='_blank'>http://stnava.github.io/ANTs/</a><a 
 id="dx1-1016"></a>                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-8-6"  
class="td11"><a 
href="#Xavants2009advanced">Avants et al.</a> <a 
href="#Xavants2009advanced">2009</a>                                                                  </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-9-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-9-1"  
class="td11">8   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-9-2"  
class="td11">elastix                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-9-3"  
class="td11">2009</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-9-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-9-5"  
class="td11">•  A general toolbox for rigid and non-rigid image registration.<br 
class="newline" />•  <a href='https://elastix.lumc.nl' target='_blank'>https://elastix.lumc.nl</a><a 
 id="dx1-1017"></a>                                                                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-9-6"  
class="td11"><a 
href="#Xklein2009elastix">Klein et al.</a> <a 
href="#Xklein2009elastix">2009</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-10-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-10-1"  
class="td11">9   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-10-2"  
class="td11">Lucas–Kanade framework</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-10-3"  
class="td11">2009</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-10-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-10-5"  
class="td11">•  Lucas-Kanade framework for non-uniform motion image registration.                                                                                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-10-6"  
class="td11"><a 
href="#Xgreenberg2009automated">Greenberg and Kerr</a> <a 
href="#Xgreenberg2009automated">2009</a>                                                        </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-11-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-11-1"  
class="td11">10  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-11-2"  
class="td11">CIRF (calcium-behavior) </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-11-3"  
class="td11">2011</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-11-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-11-5"  
class="td11">•  Regressive model to obtain Ca<sup class="textsuperscript"><span 
class="rm-lmr-10x-x-109">2+</span></sup> signal based on behavior.                                                                                                                                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-11-6"  
class="td11"><a 
href="#XMiri2011">Miri et al.</a> <a 
href="#XMiri2011">2011</a>                                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-12-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-12-1"  
class="td11">11  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-12-2"  
class="td11">openBIS                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-12-3"  
class="td11">2011</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-12-4"  
class="td11">Data handling            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-12-5"  
class="td11">•  FAIR data management.<br 
class="newline" />•  <a href='https://openbis.ch' target='_blank'>https://openbis.ch</a><a 
 id="dx1-1018"></a>                                                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-12-6"  
class="td11"><a 
href="#Xbauch2011openbis">Bauch et al.</a> <a 
href="#Xbauch2011openbis">2011</a>                                                                  </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-13-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-13-1"  
class="td11">12  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-13-2"  
class="td11">Automated ROI analysis </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-13-3"  
class="td11">2012</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-13-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-13-5"  
class="td11">•  Automatic ellipses based ROI detection.                                                                                                                                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-13-6"  
class="td11"><a 
href="#XFrancis2012">Francis et al.</a> <a 
href="#XFrancis2012">2012</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-14-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-14-1"  
class="td11">13  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-14-2"  
class="td11">OMERO                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-14-3"  
class="td11">2012</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-14-4"  
class="td11">Data handling            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-14-5"  
class="td11">•  Microscopy data handling.<br 
class="newline" />•  <a href='https://www.openmicroscopy.org' target='_blank'>https://www.openmicroscopy.org</a><a 
 id="dx1-1019"></a>                                                                                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-14-6"  
class="td11"><a 
href="#Xallan2012omero">Allan et al.</a> <a 
href="#Xallan2012omero">2012</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-15-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-15-1"  
class="td11">14  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-15-2"  
class="td11">ADINA                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-15-3"  
class="td11">2013</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-15-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-15-5"  
class="td11">•  Sparse dictionary learning.                                                                                                                                                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-15-6"  
class="td11"><a 
href="#Xdiego2013automated">Diego et al.</a> <a 
href="#Xdiego2013automated">2013</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-16-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-16-1"  
class="td11">15  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-16-2"  
class="td11">TPP                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-16-3"  
class="td11">2013</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-16-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-16-5"  
class="td11">•  Tool for processing two-photon calcium imaging data, e.g. finding cells with SeNeCA.<br 
class="newline" />•  <a href='http://uemweb.biomed.cas.cz/tpp/' target='_blank'>http://uemweb.biomed.cas.cz/tpp/</a><a 
 id="dx1-1020"></a>                                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-16-6"  
class="td11"><a 
href="#Xtomek2013two">Tomek et al.</a> <a 
href="#Xtomek2013two">2013</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-17-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-17-1"  
class="td11">16  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-17-2"  
class="td11">NMF                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-17-3"  
class="td11">2014</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-17-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-17-5"  
class="td11">•  Cell extraction using nonnegative matrix factorization (NMF). Followed by CNMF.                                                                                                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-17-6"  
class="td11"><a 
href="#Xpnevmatikakis2014structured">Pnevmatikakis et al.</a> <a 
href="#Xpnevmatikakis2014structured">2014</a>; <a 
href="#XMaruyama2014">Maruyama et al.</a> <a 
href="#XMaruyama2014">2014</a>                       </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-18-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-18-1"  
class="td11">17  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-18-2"  
class="td11">SIMA                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-18-3"  
class="td11">2014</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-18-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-18-5"  
class="td11">•  Normalized cut segmentation, motion correction, etc.<br 
class="newline" />•  <a href='https://github.com/losonczylab/sima' target='_blank'>https://github.com/losonczylab/sima</a><a 
 id="dx1-1021"></a>                                                                              </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-18-6"  
class="td11"><a 
href="#XKaifosh2014">Kaifosh et al.</a> <a 
href="#XKaifosh2014">2014</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-19-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-19-1"  
class="td11">18  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-19-2"  
class="td11">DataJoint                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-19-3"  
class="td11">2015</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-19-4"  
class="td11">Data handling            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-19-5"  
class="td11">•  Schema for data handling.<br 
class="newline" />•  <a href='https://github.com/datajoint/datajoint-matlab' target='_blank'>https://github.com/datajoint/datajoint-matlab</a><a 
 id="dx1-1022"></a>                                                                                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-19-6"  
class="td11"><a 
href="#Xyatsenko2015datajoint">Yatsenko et al.</a> <a 
href="#Xyatsenko2015datajoint">2015</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-20-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-20-1"  
class="td11">19  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-20-2"  
class="td11">NWB                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-20-3"  
class="td11">2015</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-20-4"  
class="td11">Data handling            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-20-5"  
class="td11">•  Neurodata Without Borders (NWB) initiative to produce a common data format for electrophysiology and imaging studies.<br 
class="newline" />•  <a href='https://github.com/NeurodataWithoutBorders' target='_blank'>https://github.com/NeurodataWithoutBorders</a><a 
 id="dx1-1023"></a>                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-20-6"  
class="td11"><a 
href="#XTeeters2015">Teeters et al.</a> <a 
href="#XTeeters2015">2015</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-21-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-21-1"  
class="td11">20  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-21-2"  
class="td11">Suite2p                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-21-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-21-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-21-5"  
class="td11">•  Generative model along with GUIs.                                                                                                                                                                                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-21-6"  
class="td11"><a 
href="#Xpachitariu2016suite2p">Pachitariu et al.</a> <a 
href="#Xpachitariu2016suite2p">2016</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-22-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-22-1"  
class="td11">21  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-22-2"  
class="td11">CNMF (CaImAn)          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-22-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-22-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-22-5"  
class="td11">•  Constrained NMF (CNMF).<br 
class="newline" />•  <a href='https://github.com/flatironinstitute/CaImAn-MATLAB' target='_blank'>https://github.com/flatironinstitute/CaImAn-MATLAB</a><a 
 id="dx1-1024"></a>                                                                                              </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-22-6"  
class="td11"><a 
href="#Xpnevmatikakis2016simultaneous">Pnevmatikakis et al.</a> <a 
href="#Xpnevmatikakis2016simultaneous">2016</a>                                                       </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-23-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-23-1"  
class="td11">22  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-23-2"  
class="td11">CNMF-E                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-23-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-23-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-23-5"  
class="td11">•  CNMF + background model to handle one-photon data.<br 
class="newline" />•  <a href='https://github.com/zhoupc/CNMF_E' target='_blank'>https://github.com/zhoupc/CNMF_E</a><a 
 id="dx1-1025"></a>                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-23-6"  
class="td11"><a 
href="#Xzhou2016efficient">Zhou et al.</a> <a 
href="#Xzhou2016efficient">2016</a>, <a 
href="#Xzhou2018efficient">2018</a>                                                           </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-24-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-24-1"  
class="td11">23  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-24-2"  
class="td11">Apthorpe CNN              </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-24-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-24-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-24-5"  
class="td11">•  Convolutional neural network (CNN).                                                                                                                                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-24-6"  
class="td11"><a 
href="#Xapthorpe2016automatic">Apthorpe et al.</a> <a 
href="#Xapthorpe2016automatic">2016</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-25-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-25-1"  
class="td11">24  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-25-2"  
class="td11">moco                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-25-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-25-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-25-5"  
class="td11">•  Fourier-transform based motion correction.<br 
class="newline" />•  <a href='https://github.com/NTCColumbia/moco' target='_blank'>https://github.com/NTCColumbia/moco</a><a 
 id="dx1-1026"></a>                                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-25-6"  
class="td11"><a 
href="#Xdubbs2016moco">Dubbs et al.</a> <a 
href="#Xdubbs2016moco">2016</a>                                                                  </td></tr><tr  
 style="vertical-align:baseline;" id="TBL-1-26-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-26-1"  
class="td11">25 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-26-2"  
class="td11">Cytomine </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-26-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-26-4"  
class="td11">Analysis GUI </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-26-5"  
class="td11">•  Analysis of large-scale imaging data.<br 
class="newline" />•  <a href='https://cytomine.be' target='_blank'>https://cytomine.be</a><a 
 id="dx1-1027"></a> </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-26-6"  
class="td11"><a 
href="#Xmaree2016collaborative">Marée et al.</a> <a 
href="#Xmaree2016collaborative">2016</a></td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-27-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-27-1"  
class="td11">26  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-27-2"  
class="td11">ROI clustering               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-27-3"  
class="td11">2016</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-27-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-27-5"  
class="td11">•  Select high-intensity pixels then perform clustering to segment.<br 
class="newline" />•  <a href='https://www.bu.edu/hanlab/files/2016/02/pfgc.zip' target='_blank'>https://www.bu.edu/hanlab/files/2016/02/pfgc.zip</a><a 
 id="dx1-1028"></a>                                                                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-27-6"  
class="td11"><a 
href="#Xmohammed2016integrative">Mohammed et al.</a> <a 
href="#Xmohammed2016integrative">2016</a>                                                           </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-28-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-28-1"  
class="td11">27  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-28-2"  
class="td11"><span 
class="rm-lmbx-12">CELLMax </span>(conference) </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-28-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-28-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-28-5"  
class="td11">•  Cell segmentation and activity trace extraction using a maximum likelihood approach.                                                                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-28-6"  
class="td11"><a 
href="#XAhanonu2018sfnposter">Ahanonu et al.</a> <a 
href="#XAhanonu2018sfnposter">2018</a>, <a 
href="#XAhanonu2017sfnposter">2017</a>; <a 
href="#Xahanonu2018neural">Ahanonu</a> <a 
href="#Xahanonu2018neural">2018</a>                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-29-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-29-1"  
class="td11">28  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-29-2"  
class="td11">sc-CNMF                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-29-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-29-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-29-5"  
class="td11">•  CNMF + GMM/RNN seed cleansing.                                                                                                                                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-29-6"  
class="td11"><a 
href="#Xlu2017seeds">Lu et al.</a> <a 
href="#Xlu2017seeds">2017</a>                                                                       </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-30-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-30-1"  
class="td11">29  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-30-2"  
class="td11">OASIS                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-30-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-30-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-30-5"  
class="td11">•  Generalized pool adjacent violators algorithm.<br 
class="newline" />•  <a href='https://github.com/zhoupc/OASIS_matlab' target='_blank'>https://github.com/zhoupc/OASIS_matlab</a><a 
 id="dx1-1029"></a>                                                                                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-30-6"  
class="td11"><a 
href="#Xfriedrich2017fast">Friedrich et al.</a> <a 
href="#Xfriedrich2017fast">2017</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-31-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-31-1"  
class="td11">30  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-31-2"  
class="td11">ABLE                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-31-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-31-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-31-5"  
class="td11">•  Multiple active contours and a cost function to identify cells in 2P data.<br 
class="newline" />•  <a href='https://github.com/StephanieRey/ABLE' target='_blank'>https://github.com/StephanieRey/ABLE</a><a 
 id="dx1-1030"></a>                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-31-6"  
class="td11"><a 
href="#Xreynolds2017able">Reynolds et al.</a> <a 
href="#Xreynolds2017able">2017</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-32-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-32-1"  
class="td11">31  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-32-2"  
class="td11">SCALPEL                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-32-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-32-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-32-5"  
class="td11">•  Dictionary learning, dissimilarity, and clustering.<br 
class="newline" />•  <a href='https://cran.r-project.org/web/packages/scalpel/index.html' target='_blank'>https://cran.r-project.org/web/packages/scalpel/index.html</a><a 
 id="dx1-1031"></a>                                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-32-6"  
class="td11"><a 
href="#Xpetersen2017scalpel">Petersen et al.</a> <a 
href="#Xpetersen2017scalpel">2017</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-33-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-33-1"  
class="td11">32  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-33-2"  
class="td11">HNCcorr                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-33-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-33-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-33-5"  
class="td11">•  Combinatorial optimization (correlation space analysis).<br 
class="newline" />•  <a href='https://github.com/hochbaumGroup/HNCcorr' target='_blank'>https://github.com/hochbaumGroup/HNCcorr</a><a 
 id="dx1-1032"></a>                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-33-6"  
class="td11"><a 
href="#Xspaen2017hnccorr">Spaen et al.</a> <a 
href="#Xspaen2017hnccorr">2017</a>                                                                  </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-34-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-34-1"  
class="td11">33  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-34-2"  
class="td11">OnACID                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-34-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-34-4"  
class="td11">Cell extraction (online) </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-34-5"  
class="td11">•  NMF variant for online Ca<sup class="textsuperscript"><span 
class="rm-lmr-10x-x-109">2+</span></sup> imaging processing.                                                                                                                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-34-6"  
class="td11"><a 
href="#Xgiovannucci2017onacid">Giovannucci et al.</a> <a 
href="#Xgiovannucci2017onacid">2017</a>                                                          </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-35-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-35-1"  
class="td11">34  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-35-2"  
class="td11">EXTRACT                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-35-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-35-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-35-5"  
class="td11">•  Robust statistical estimation.                                                                                                                                                                                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-35-6"  
class="td11"><a 
href="#Xinan2017robust">Inan et al.</a> <a 
href="#Xinan2017robust">2017</a>                                                                    </td></tr><tr  
 style="vertical-align:baseline;" id="TBL-1-36-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-36-1"  
class="td11">35 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-36-2"  
class="td11">NETCAL </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-36-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-36-4"  
class="td11">Analysis pipeline </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-36-5"  
class="td11">•  Calcium imaging analysis GUI.<br 
class="newline" />•  <a href='https://github.com/orlandi/netcal' target='_blank'>https://github.com/orlandi/netcal</a><a 
 id="dx1-1033"></a> </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-36-6"  
class="td11"><a 
href="#Xorlandinetcal">Orlandi et al.</a></td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-37-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-37-1"  
class="td11">36  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-37-2"  
class="td11">NoRMCorre                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-37-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-37-4"  
class="td11">Motion correction.       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-37-5"  
class="td11">•  Piecewise rigid motion correction.<br 
class="newline" />•  <a href='https://github.com/simonsfoundation/NoRMCorre' target='_blank'>https://github.com/simonsfoundation/NoRMCorre</a><a 
 id="dx1-1034"></a>                                                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-37-6"  
class="td11"><a 
href="#Xpnevmatikakis2017normcorre">Pnevmatikakis and Giovannucci</a> <a 
href="#Xpnevmatikakis2017normcorre">2017</a>                                        </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-38-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-38-1"  
class="td11">37  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-38-2"  
class="td11">CellReg                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-38-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-38-4"  
class="td11">Cross-session alignment</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-38-5"  
class="td11">•  Alignment of cells across days using a probabilistic approach.<br 
class="newline" />•  <a href='https://github.com/zivlab/CellReg' target='_blank'>https://github.com/zivlab/CellReg</a><a 
 id="dx1-1035"></a>                                                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-38-6"  
class="td11"><a 
href="#Xsheintuch2017tracking">Sheintuch et al.</a> <a 
href="#Xsheintuch2017tracking">2017</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-39-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-39-1"  
class="td11">38  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-39-2"  
class="td11">NeuroSeg                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-39-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-39-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-39-5"  
class="td11">•  Filtering and seed/clustering based cell segmentation.<br 
class="newline" />•  <a href='https://github.com/baidatong/NeuroSeg' target='_blank'>https://github.com/baidatong/NeuroSeg</a><a 
 id="dx1-1036"></a>                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-39-6"  
class="td11"><a 
href="#Xguan2018neuroseg">Guan et al.</a> <a 
href="#Xguan2018neuroseg">2018</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-40-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-40-1"  
class="td11">39  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-40-2"  
class="td11">CNMF-E+                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-40-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-40-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-40-5"  
class="td11">•  Shrinkage estimation to improve CNMF-E initialization.                                                                                                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-40-6"  
class="td11"><a 
href="#Xtakekawa2017automatic">Takekawa et al.</a> <a 
href="#Xtakekawa2017automatic">2017</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-41-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-41-1"  
class="td11">40  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-41-2"  
class="td11">Toolbox-Romano           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-41-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-41-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-41-5"  
class="td11">•  Full analysis pipeline with ROI-based segmentation<br 
class="newline" />•  <a href='https://github.com/zebrain-lab/Toolbox-Romano-et-al' target='_blank'>https://github.com/zebrain-lab/Toolbox-Romano-et-al</a><a 
 id="dx1-1037"></a>                                                                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-41-6"  
class="td11"><a 
href="#Xromano2017integrated">Romano et al.</a> <a 
href="#Xromano2017integrated">2017</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-42-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-42-1"  
class="td11">41  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-42-2"  
class="td11">SamuROI                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-42-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-42-4"  
class="td11">Analysis GUI             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-42-5"  
class="td11">•  GUI for data visualization<br 
class="newline" />•  <a href='https://github.com/samuroi/SamuROI' target='_blank'>https://github.com/samuroi/SamuROI</a><a 
 id="dx1-1038"></a>                                                                                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-42-6"  
class="td11"><a 
href="#Xrueckl2017samuroi">Rueckl et al.</a> <a 
href="#Xrueckl2017samuroi">2017</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-43-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-43-1"  
class="td11">42  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-43-2"  
class="td11">KNIME                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-43-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-43-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-43-5"  
class="td11">•  Workflow manager for data analysis.<br 
class="newline" />•  <a href='https://www.knime.com' target='_blank'>https://www.knime.com</a><a 
 id="dx1-1039"></a>                                                                                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-43-6"  
class="td11"><a 
href="#Xfillbrunn2017knime">Fillbrunn et al.</a> <a 
href="#Xfillbrunn2017knime">2017</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-44-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-44-1"  
class="td11">43  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-44-2"  
class="td11">U-Net2DS                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-44-3"  
class="td11">2017</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-44-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-44-5"  
class="td11">•  Evaluated several deep learning models on Neurofinder, U-Net2DS best.<br 
class="newline" />•  <a href='https://github.com/alexklibisz/deep-calcium' target='_blank'>https://github.com/alexklibisz/deep-calcium</a><a 
 id="dx1-1040"></a>                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-44-6"  
class="td11"><a 
href="#Xklibisz2017fast">Klibisz et al.</a> <a 
href="#Xklibisz2017fast">2017</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-45-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-45-1"  
class="td11">44  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-45-2"  
class="td11"><span 
class="rm-lmbx-12">CLEAN </span>(conference)     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-45-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-45-4"  
class="td11">Cell sorting                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-45-5"  
class="td11">•  Machine learning based cell sorting of cell extraction outputs based on image and activity trace features.                                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-45-6"  
class="td11"><a 
href="#XAhanonu2018sfnposter">Ahanonu et al.</a> <a 
href="#XAhanonu2018sfnposter">2018</a>; <a 
href="#Xahanonu2018neural">Ahanonu</a> <a 
href="#Xahanonu2018neural">2018</a>                                         </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-46-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-46-1"  
class="td11">45  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-46-2"  
class="td11">FISSA                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-46-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-46-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-46-5"  
class="td11">•  Neuropil decontamination using local region around cell.<br 
class="newline" />•  <a href='https://github.com/rochefort-lab/fissa' target='_blank'>https://github.com/rochefort-lab/fissa</a><a 
 id="dx1-1041"></a>                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-46-6"  
class="td11"><a 
href="#Xkeemink2018fissa">Keemink et al.</a> <a 
href="#Xkeemink2018fissa">2018</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-47-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-47-1"  
class="td11">46  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-47-2"  
class="td11">LSSC                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-47-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-47-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-47-5"  
class="td11">•  Spectral clustering; variant to find local subset of eigenvectors.                                                                                                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-47-6"  
class="td11"><a 
href="#Xmishne2018automated">Mishne et al.</a> <a 
href="#Xmishne2018automated">2018</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-48-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-48-1"  
class="td11">47  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-48-2"  
class="td11">PMD - PCA                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-48-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-48-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-48-5"  
class="td11">•  Spatially-localized penalized matrix decomposition for denoising; compression; and improved demixing.<br 
class="newline" />•  <a href='https://github.com/paninski-lab/funimag' target='_blank'>https://github.com/paninski-lab/funimag</a><a 
 id="dx1-1042"></a>                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-48-6"  
class="td11"><a 
href="#Xbuchanan2018penalized">Buchanan et al.</a> <a 
href="#Xbuchanan2018penalized">2018</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-49-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-49-1"  
class="td11">48  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-49-2"  
class="td11">MIN1PIPE                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-49-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-49-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-49-5"  
class="td11">•  Pre-processing to enhance neural signals then sc-CNMF for cell extraction.                                                                                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-49-6"  
class="td11"><a 
href="#XLu2018min1pipe">Lu et al.</a> <a 
href="#XLu2018min1pipe">2018</a>                                                                       </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-50-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-50-1"  
class="td11">49  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-50-2"  
class="td11">CaImAn (preprint)         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-50-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-50-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-50-5"  
class="td11">•  CNMF + several other processing tools.                                                                                                                                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-50-6"  
class="td11"><a 
href="#XGiovannucci2018">Giovannucci et al.</a> <a 
href="#XGiovannucci2018">2018</a>                                                          </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-51-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-51-1"  
class="td11">50  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-51-2"  
class="td11">SEUDO (preprint)         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-51-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-51-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-51-5"  
class="td11">•  Mixture of Gaussians + maximum likelihood; post-hoc activity trace correction.                                                                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-51-6"  
class="td11"><a 
href="#Xgauthier2018detecting">Gauthier et al.</a> <a 
href="#Xgauthier2018detecting">2018</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-52-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-52-1"  
class="td11">51  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-52-2"  
class="td11">ACSAT                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-52-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-52-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-52-5"  
class="td11">•  Global and local adaptive thresholding to identify neurons.<br 
class="newline" />•  <a href='https://github.com/sshen8/acsat' target='_blank'>https://github.com/sshen8/acsat</a><a 
 id="dx1-1043"></a>                                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-52-6"  
class="td11"><a 
href="#Xshen2018automatic">Shen et al.</a> <a 
href="#Xshen2018automatic">2018</a>                                                                    </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-53-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-53-1"  
class="td11">52  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-53-2"  
class="td11">onlineMotionCorrection   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-53-3"  
class="td11">2018</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-53-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-53-5"  
class="td11">•  Tested multiple algorithms and developed an online motion correction pipeline.<br 
class="newline" />•  <a href='https://github.com/amitani/onlineMotionCorrection' target='_blank'>https://github.com/amitani/onlineMotionCorrection</a><a 
 id="dx1-1044"></a>                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-53-6"  
class="td11"><a 
href="#Xmitani2018real">Mitani and Komiyama</a> <a 
href="#Xmitani2018real">2018</a>                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-54-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-54-1"  
class="td11">53  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-54-2"  
class="td11"><span 
class="rm-lmbx-12">CIAtah                    </span></td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-54-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-54-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-54-5"  
class="td11">•  1P and 2P Imaging analysis pipeline supporting PCA-ICA, CNMF, CELLMax, EXTRACT, etc.<br 
class="newline" />•  <a href='https://github.com/bahanonu/ciatah' target='_blank'>https://github.com/bahanonu/ciatah</a><a 
 id="dx1-1045"></a>                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-54-6"  
class="td11"><a 
href="#Xcorder2019amygdalar">Corder et al.</a> <a 
href="#Xcorder2019amygdalar">2019</a>; <a 
href="#Xahanonu2018neural">Ahanonu</a> <a 
href="#Xahanonu2018neural">2018</a>; <a 
href="#Xahanonu2022recording">Ahanonu and Corder</a> <a 
href="#Xahanonu2022recording">2022</a>      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-55-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-55-1"  
class="td11">54  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-55-2"  
class="td11">NAOMi (bioRxiv)          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-55-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-55-4"  
class="td11">Simulator                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-55-5"  
class="td11">•  Generative model for creating simulated calcium imaging movies.                                                                                                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-55-6"  
class="td11"><a 
href="#Xcharles2019neural">Charles et al.</a> <a 
href="#Xcharles2019neural">2019</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-56-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-56-1"  
class="td11">55  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-56-2"  
class="td11">CALIMA                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-56-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-56-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-56-5"  
class="td11">•  Calcium imaging analysis GUI.                                                                                                                                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-56-6"  
class="td11"><a 
href="#Xradstake2019calima">Radstake et al.</a> <a 
href="#Xradstake2019calima">2019</a>                                                              </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-57-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-57-1"  
class="td11">56  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-57-2"  
class="td11">STNeuroNet                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-57-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-57-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-57-5"  
class="td11">•  Convolutional neural network to detect and segment cells.                                                                                                                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-57-6"  
class="td11"><a 
href="#Xsoltanian2019fast">Soltanian-Zadeh et al.</a> <a 
href="#Xsoltanian2019fast">2019</a>                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-58-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-58-1"  
class="td11">57  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-58-2"  
class="td11">AQuA                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-58-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-58-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-58-5"  
class="td11">•  Astrocyte imaging focused. Non-ROI cluster and propagation based detection of events.                                                                                                                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-58-6"  
class="td11"><a 
href="#Xwang2019accurate">Wang et al.</a> <a 
href="#Xwang2019accurate">2019</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-59-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-59-1"  
class="td11">58  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-59-2"  
class="td11">CaImAn                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-59-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-59-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-59-5"  
class="td11">•  Popular calcium imaging pipeline that includes CNMF + several other processing tools.<br 
class="newline" />•  <a href='https://github.com/flatironinstitute/CaImAn' target='_blank'>https://github.com/flatironinstitute/CaImAn</a><a 
 id="dx1-1046"></a>                                                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-59-6"  
class="td11"><a 
href="#Xgiovannucci2019caiman">Giovannucci et al.</a> <a 
href="#Xgiovannucci2019caiman">2019</a>                                                          </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-60-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-60-1"  
class="td11">59  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-60-2"  
class="td11">DL+RWL1-SF              </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-60-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-60-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-60-5"  
class="td11">•  Dictionary learning and spatial correlation based cell extraction.                                                                                                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-60-6"  
class="td11"><a 
href="#Xmishne2019learning">Mishne and Charles</a> <a 
href="#Xmishne2019learning">2019</a>                                                        </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-61-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-61-1"  
class="td11">60  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-61-2"  
class="td11">Segment2P                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-61-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-61-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-61-5"  
class="td11">•  Pre-process images and run through DeepLabV3.<br 
class="newline" />•  <a href='https://github.com/NoahDolev/Segment2P' target='_blank'>https://github.com/NoahDolev/Segment2P</a><a 
 id="dx1-1047"></a>                                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-61-6"  
class="td11"><a 
href="#Xdolev2019segment2p">Dolev et al.</a> <a 
href="#Xdolev2019segment2p">2019</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-62-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-62-1"  
class="td11">61  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-62-2"  
class="td11">LANMC                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-62-3"  
class="td11">2019</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-62-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-62-5"  
class="td11">•  Long short-term memory non-rigid motion correction, reduce computational cost by predicting non-rigid motion.                                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-62-6"  
class="td11"><a 
href="#Xchen2019lanmc">Chen et al.</a> <a 
href="#Xchen2019lanmc">2019</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-63-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-63-1"  
class="td11">62  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-63-2"  
class="td11">marked point processes   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-63-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-63-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-63-5"  
class="td11">•  Probabilistic generative model, specifically a marked point process, to extract activity traces.                                                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-63-6"  
class="td11"><a 
href="#Xshibue2020deconvolution">Shibue and Komaki</a> <a 
href="#Xshibue2020deconvolution">2020</a>                                                         </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-64-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-64-1"  
class="td11">63  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-64-2"  
class="td11">LocaNMF                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-64-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-64-4"  
class="td11">Region extraction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-64-5"  
class="td11">•  Localized semi-nonnegative matrix factorization for extracting active regions.<br 
class="newline" />•  <a href='https://github.com/ikinsella/locaNMF' target='_blank'>https://github.com/ikinsella/locaNMF</a><a 
 id="dx1-1048"></a>                                                              </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-64-6"  
class="td11"><a 
href="#Xsaxena2020localized">Saxena et al.</a> <a 
href="#Xsaxena2020localized">2020</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-65-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-65-1"  
class="td11">64  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-65-2"  
class="td11">EZcalcium                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-65-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-65-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-65-5"  
class="td11">•  Calcium imaging analysis toolbox.<br 
class="newline" />•  <a href='https://github.com/porteralab/EZcalcium' target='_blank'>https://github.com/porteralab/EZcalcium</a><a 
 id="dx1-1049"></a>                                                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-65-6"  
class="td11"><a 
href="#Xcantu2020ezcalcium">Cantu et al.</a> <a 
href="#Xcantu2020ezcalcium">2020</a>                                                                  </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-66-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-66-1"  
class="td11">65  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-66-2"  
class="td11">OnACID-E + ring CNN  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-66-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-66-4"  
class="td11">Cell extraction (online) </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-66-5"  
class="td11">•  OnACID for miniscope and new ring CNN background model to improve accuracy.<br 
class="newline" />•  <a href='https://github.com/flatironinstitute/CaImAn' target='_blank'>https://github.com/flatironinstitute/CaImAn</a><a 
 id="dx1-1050"></a>                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-66-6"  
class="td11"><a 
href="#Xfriedrich2020online">Friedrich et al.</a> <a 
href="#Xfriedrich2020online">2020</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-67-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-67-1"  
class="td11">66  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-67-2"  
class="td11">Auto CNMF-E sorting    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-67-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-67-4"  
class="td11">Cell sorting                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-67-5"  
class="td11">•  Machine learning (AutoML) based curation of CNMF-E outputs.<br 
class="newline" />•  <a href='https://github.com/jf-lab/cnmfe-reviewer' target='_blank'>https://github.com/jf-lab/cnmfe-reviewer</a><a 
 id="dx1-1051"></a>                                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-67-6"  
class="td11"><a 
href="#Xtran2020automated">Tran et al.</a> <a 
href="#Xtran2020automated">2020a</a>,<a 
href="#Xtran2020automated2">b</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-68-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-68-1"  
class="td11">67  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-68-2"  
class="td11">DeepInterpolation          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-68-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-68-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-68-5"  
class="td11">•  Encoder-decoder architecture with 2D conv. to denoise imaging data.<br 
class="newline" />•  <a href='https://github.com/AllenInstitute/deepinterpolation' target='_blank'>https://github.com/AllenInstitute/deepinterpolation</a><a 
 id="dx1-1052"></a>                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-68-6"  
class="td11"><a 
href="#Xlecoq2020removing">Lecoq et al.</a> <a 
href="#Xlecoq2020removing">2020</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-69-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-69-1"  
class="td11">68  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-69-2"  
class="td11">BIAFLOWS                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-69-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-69-4"  
class="td11">Benchmarking            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-69-5"  
class="td11">•  Framework for benchmarking imaging analysis workflows.<br 
class="newline" />•  <a href='https://biaflows.neubias.org' target='_blank'>https://biaflows.neubias.org</a><a 
 id="dx1-1053"></a>                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-69-6"  
class="td11"><a 
href="#Xrubens2020biaflows">Rubens et al.</a> <a 
href="#Xrubens2020biaflows">2020</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-70-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-70-1"  
class="td11">69  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-70-2"  
class="td11">FIBSI                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-70-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-70-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-70-5"  
class="td11">•  Extension of Ramer-Douglas-Peucker algorithm to identify baseline that is used for signal detection.<br 
class="newline" />•  <a href='https://github.com/rmcassidy/FIBSI_program' target='_blank'>https://github.com/rmcassidy/FIBSI_program</a><a 
 id="dx1-1054"></a>                                               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-70-6"  
class="td11"><a 
href="#Xcassidy2020frequency">Cassidy et al.</a> <a 
href="#Xcassidy2020frequency">2020</a>; <a 
href="#Xalles2021chronic">Alles et al.</a> <a 
href="#Xalles2021chronic">2021</a>                                       </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-71-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-71-1"  
class="td11">70  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-71-2"  
class="td11">DISCo                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-71-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-71-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-71-5"  
class="td11">•  Pixel correlation and deep learning (CNN) + graph based segmentation.<br 
class="newline" />•  <a href='https://github.com/EKirschbaum/DISCo' target='_blank'>https://github.com/EKirschbaum/DISCo</a><a 
 id="dx1-1055"></a>                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-71-6"  
class="td11"><a 
href="#Xkirschbaum2020disco">Kirschbaum et al.</a> <a 
href="#Xkirschbaum2020disco">2020</a>                                                           </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-72-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-72-1"  
class="td11">71  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-72-2"  
class="td11">DeepCINAC                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-72-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-72-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-72-5"  
class="td11">•  Trace analysis after human labeling followed by CNNs + bidirectional long-short term memory (LSTM) network.<br 
class="newline" />•  <a href='https://gitlab.com/cossartlab/deepcinac' target='_blank'>https://gitlab.com/cossartlab/deepcinac</a><a 
 id="dx1-1056"></a>                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-72-6"  
class="td11"><a 
href="#Xdenis2020deepcinac">Denis et al.</a> <a 
href="#Xdenis2020deepcinac">2020</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-73-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-73-1"  
class="td11">72  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-73-2"  
class="td11">NDSEP                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-73-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-73-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-73-5"  
class="td11">•  Dataflow framework for real-time calcium imaging processing.<br 
class="newline" />•  <a href='http://dspcad-www.iacs.umd.edu/bcnm/index.html' target='_blank'>http://dspcad-www.iacs.umd.edu/bcnm/index.html</a><a 
 id="dx1-1057"></a>                                                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-73-6"  
class="td11"><a 
href="#Xlee2020real">Lee et al.</a> <a 
href="#Xlee2020real">2020</a>                                                                      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-74-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-74-1"  
class="td11">73  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-74-2"  
class="td11">DeepBrainSeg               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-74-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-74-4"  
class="td11">Segmentation             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-74-5"  
class="td11">•  Dual-pathway CNN to learn local and contextual features.                                                                                                                                                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-74-6"  
class="td11"><a 
href="#Xtan2020deepbrainseg">Tan et al.</a> <a 
href="#Xtan2020deepbrainseg">2020</a>                                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-75-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-75-1"  
class="td11">74  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-75-2"  
class="td11">RT-3DMC                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-75-3"  
class="td11">2020</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-75-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-75-5"  
class="td11">•  Bead or soma tracking for real-time motion correction during 2P imaging.<br 
class="newline" />•  <a href='https://github.com/SilverLabUCL/SilverLab-Microscope' target='_blank'>https://github.com/SilverLabUCL/SilverLab-Microscope</a><a 
 id="dx1-1058"></a>                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-75-6"  
class="td11"><a 
href="#Xgriffiths2020real">Griffiths et al.</a> <a 
href="#Xgriffiths2020real">2020</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-76-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-76-1"  
class="td11">75  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-76-2"  
class="td11">Cellpose                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-76-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-76-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-76-5"  
class="td11">•  Neural network and gradient-based cell segmentation.<br 
class="newline" />•  <a href='https://github.com/mouseland/cellpose' target='_blank'>https://github.com/mouseland/cellpose</a><a 
 id="dx1-1059"></a>                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-76-6"  
class="td11"><a 
href="#Xstringer2021cellpose">Stringer et al.</a> <a 
href="#Xstringer2021cellpose">2021</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-77-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-77-1"  
class="td11">76  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-77-2"  
class="td11">NAOMi                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-77-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-77-4"  
class="td11">Simulator                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-77-5"  
class="td11">•  Detailed model simulation for benchmarking calcium imaging algorithms.<br 
class="newline" />•  <a href='https://bitbucket.org/adamshch/naomi_sim/src/master/' target='_blank'>https://bitbucket.org/adamshch/naomi_sim/src/master/</a><a 
 id="dx1-1060"></a>                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-77-6"  
class="td11"><a 
href="#Xsong2021neural">Song et al.</a> <a 
href="#Xsong2021neural">2021</a>                                                                    </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-78-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-78-1"  
class="td11">77  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-78-2"  
class="td11">OnACID-E + ring CNN  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-78-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-78-4"  
class="td11">Cell extraction (online) </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-78-5"  
class="td11">•  OnACID for 1P data and ring CNN background model.<br 
class="newline" />•  <a href='https://github.com/flatironinstitute/CaImAn' target='_blank'>https://github.com/flatironinstitute/CaImAn</a><a 
 id="dx1-1061"></a>                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-78-6"  
class="td11"><a 
href="#Xfriedrich2021online">Friedrich et al.</a> <a 
href="#Xfriedrich2021online">2021</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-79-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-79-1"  
class="td11">78  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-79-2"  
class="td11">EXTRACT                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-79-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-79-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-79-5"  
class="td11">•  Robust statistics based cell extraction.<br 
class="newline" />•  <a href='https://github.com/schnitzer-lab/EXTRACT-public' target='_blank'>https://github.com/schnitzer-lab/EXTRACT-public</a><a 
 id="dx1-1062"></a>                                                                                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-79-6"  
class="td11"><a 
href="#Xinan2021fast">Inan et al.</a> <a 
href="#Xinan2021fast">2021</a>                                                                    </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-80-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-80-1"  
class="td11">79  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-80-2"  
class="td11">Minian                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-80-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-80-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-80-5"  
class="td11">•  Imaging analysis pipeline with CNMF for cell extraction, in part using Jupyter notebooks with GUI elements.<br 
class="newline" />•  <a href='https://github.com/DeniseCaiLab/minian' target='_blank'>https://github.com/DeniseCaiLab/minian</a><a 
 id="dx1-1063"></a>                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-80-6"  
class="td11"><a 
href="#Xdong2021minian">Dong et al.</a> <a 
href="#Xdong2021minian">2021</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-81-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-81-1"  
class="td11">80  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-81-2"  
class="td11">Mesmerize                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-81-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-81-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-81-5"  
class="td11">•  Imaging analysis platform with CaImAn for cell extraction, import support for other cell extraction algorithms.<br 
class="newline" />•  <a href='https://github.com/kushalkolar/MESmerize' target='_blank'>https://github.com/kushalkolar/MESmerize</a><a 
 id="dx1-1064"></a>                                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-81-6"  
class="td11"><a 
href="#Xkolar2021mesmerize">Kolar et al.</a> <a 
href="#Xkolar2021mesmerize">2021</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-82-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-82-1"  
class="td11">81  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-82-2"  
class="td11">DeepInterpolation          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-82-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-82-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-82-5"  
class="td11">•  Encoder-decoder architecture with 2D conv. to denoise imaging data.<br 
class="newline" />•  <a href='https://github.com/AllenInstitute/deepinterpolation' target='_blank'>https://github.com/AllenInstitute/deepinterpolation</a><a 
 id="dx1-1065"></a>                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-82-6"  
class="td11"><a 
href="#Xlecoq2021removing">Lecoq et al.</a> <a 
href="#Xlecoq2021removing">2021</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-83-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-83-1"  
class="td11">82  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-83-2"  
class="td11">BEAR                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-83-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-83-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-83-5"  
class="td11">•  Neural network approximation of PCA for cell extraction.<br 
class="newline" />•  <a href='https://github.com/NICALab/BEAR' target='_blank'>https://github.com/NICALab/BEAR</a><a 
 id="dx1-1066"></a>                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-83-6"  
class="td11"><a 
href="#Xhan2021efficient">Han et al.</a> <a 
href="#Xhan2021efficient">2021</a>                                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-84-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-84-1"  
class="td11">83  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-84-2"  
class="td11">CaPTure                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-84-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-84-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-84-5"  
class="td11">•  ROI segmentation and activity extraction.<br 
class="newline" />•  <a href='https://github.com/LieberInstitute/CaPTure' target='_blank'>https://github.com/LieberInstitute/CaPTure</a><a 
 id="dx1-1067"></a>                                                                                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-84-6"  
class="td11"><a 
href="#Xtippani2021capture">Tippani et al.</a> <a 
href="#Xtippani2021capture">2021</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-85-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-85-1"  
class="td11">84  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-85-2"  
class="td11">CASCADE                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-85-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-85-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-85-5"  
class="td11">•  Spike inference based on dual ephys/calcium imaging recordings.<br 
class="newline" />•  <a href='https://github.com/HelmchenLabSoftware/Cascade' target='_blank'>https://github.com/HelmchenLabSoftware/Cascade</a><a 
 id="dx1-1068"></a>                                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-85-6"  
class="td11"><a 
href="#Xrupprecht2021database">Rupprecht et al.</a> <a 
href="#Xrupprecht2021database">2021</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-86-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-86-1"  
class="td11">85  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-86-2"  
class="td11">VolPy                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-86-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-86-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-86-5"  
class="td11">•  Voltage imaging analysis pipeline integrated into CaImAn.<br 
class="newline" />•  <a href='https://github.com/flatironinstitute/CaImAn' target='_blank'>https://github.com/flatironinstitute/CaImAn</a><a 
 id="dx1-1069"></a>                                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-86-6"  
class="td11"><a 
href="#Xcai2021volpy">Cai et al.</a> <a 
href="#Xcai2021volpy">2021</a>                                                                      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-87-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-87-1"  
class="td11">86  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-87-2"  
class="td11">DeepCAD                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-87-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-87-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-87-5"  
class="td11">•  Deep neural network based denoising.<br 
class="newline" />•  <a href='https://github.com/cabooster/DeepCAD-RT' target='_blank'>https://github.com/cabooster/DeepCAD-RT</a><a 
 id="dx1-1070"></a>                                                                                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-87-6"  
class="td11"><a 
href="#Xli2021reinforcing">Li et al.</a> <a 
href="#Xli2021reinforcing">2021</a>                                                                        </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-88-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-88-1"  
class="td11">87  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-88-2"  
class="td11">SpecSeg                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-88-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-88-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-88-5"  
class="td11">•  Spectral density of pixels to identify ROIs. Also incorporates motion correction and cross-session matching.<br 
class="newline" />•  <a href='https://github.com/Leveltlab/SpectralSegmentation' target='_blank'>https://github.com/Leveltlab/SpectralSegmentation</a><a 
 id="dx1-1071"></a>                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-88-6"  
class="td11"><a 
href="#Xde2021specseg">de Kraker et al.</a> <a 
href="#Xde2021specseg">2021</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-89-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-89-1"  
class="td11">88  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-89-2"  
class="td11">FIOLA                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-89-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-89-4"  
class="td11">Cell extraction (online) </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-89-5"  
class="td11">•  GPU- and computational graph-based speed-ups along with non-negative least squares for post-initialization signal extraction.<br 
class="newline" />•  <a href='https://github.com/nel-lab/FIOLA' target='_blank'>https://github.com/nel-lab/FIOLA</a><a 
 id="dx1-1072"></a>                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-89-6"  
class="td11"><a 
href="#Xgiovannucci2021fiola">Giovannucci et al.</a> <a 
href="#Xgiovannucci2021fiola">2021</a>                                                          </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-90-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-90-1"  
class="td11">89  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-90-2"  
class="td11">PatchWarp                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-90-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-90-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-90-5"  
class="td11">•  Affine transformation of subfields followed by stitching subfields together.<br 
class="newline" />•  <a href='https://github.com/ryhattori/PatchWarp' target='_blank'>https://github.com/ryhattori/PatchWarp</a><a 
 id="dx1-1073"></a>                                                                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-90-6"  
class="td11"><a 
href="#XHattori2021.11.10.468164">Hattori and Komiyama</a> <a 
href="#XHattori2021.11.10.468164">2021</a>                                                    </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-91-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-91-1"  
class="td11">90  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-91-2"  
class="td11">MVG-CNN                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-91-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-91-4"  
class="td11">Region extraction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-91-5"  
class="td11">•  Automated sleep states classification using multiplex visibility graphs and deep learning. <a href='https://physionet.org/content/calcium-imaging-sleep-state/1.0.0/' target='_blank'>Data URL</a><a 
 id="dx1-1074"></a>.<br 
class="newline" />•  <a href='https://github.com/comp-imaging-sci/MVG-CNN' target='_blank'>https://github.com/comp-imaging-sci/MVG-CNN</a><a 
 id="dx1-1075"></a>                                                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-91-6"  
class="td11"><a 
href="#Xzhang2021automated">Zhang et al.</a> <a 
href="#Xzhang2021automated">2021</a>                                                                  </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-92-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-92-1"  
class="td11">91  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-92-2"  
class="td11">Flow-Registration          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-92-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-92-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-92-5"  
class="td11">•  Variational optical flow for non-uniform motion correction<br 
class="newline" />•  <a href='https://github.com/phflot/flow_registration' target='_blank'>https://github.com/phflot/flow_registration</a><a 
 id="dx1-1076"></a>                                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-92-6"  
class="td11"><a 
href="#Xflotho2022software">Flotho et al.</a> <a 
href="#Xflotho2022software">2022</a>                                                                  </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-93-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-93-1"  
class="td11">92  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-93-2"  
class="td11">SUNS                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-93-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-93-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-93-5"  
class="td11">•  Cell segmentation using shallow U-Nets.<br 
class="newline" />•  <a href='https://github.com/YijunBao/Shallow-UNet-Neuron-Segmentation_SUNS' target='_blank'>https://github.com/YijunBao/Shallow-UNet-Neuron-Segmentation_SUNS</a><a 
 id="dx1-1077"></a>                                                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-93-6"  
class="td11"><a 
href="#Xbao2021segmentation">Bao et al.</a> <a 
href="#Xbao2021segmentation">2021</a>                                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-94-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-94-1"  
class="td11">93  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-94-2"  
class="td11">Carignan                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-94-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-94-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-94-5"  
class="td11">•  Online cell extraction and triggering based on OnACID and CaImAn.<br 
class="newline" />•  <a href='https://github.com/tzklab/carignan' target='_blank'>https://github.com/tzklab/carignan</a><a 
 id="dx1-1078"></a>                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-94-6"  
class="td11"><a 
href="#Xtaniguchi2021open">Taniguchi et al.</a> <a 
href="#Xtaniguchi2021open">2021</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-95-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-95-1"  
class="td11">94  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-95-2"  
class="td11">MullenClassifier             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-95-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-95-4"  
class="td11">Cell sorting                </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-95-5"  
class="td11">•  Feature extraction from cell images and tracs followed by supervised learning classifier.                                                                                                                   </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-95-6"  
class="td11"><a 
href="#Xmullen2021automated">Mullen et al.</a> <a 
href="#Xmullen2021automated">2021</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-96-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-96-1"  
class="td11">95  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-96-2"  
class="td11">timeUnet                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-96-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-96-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-96-5"  
class="td11">•  Deep learning for denoising with temporal information added in.<br 
class="newline" />•  <a href='https://github.com/BoHuangLab/Transfer-Learning-Denoising/' target='_blank'>https://github.com/BoHuangLab/Transfer-Learning-Denoising/</a><a 
 id="dx1-1079"></a>                                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-96-6"  
class="td11"><a 
href="#Xwang2021image">Wang et al.</a> <a 
href="#Xwang2021image">2021</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-97-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-97-1"  
class="td11">96  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-97-2"  
class="td11">EMC<sup class="textsuperscript"><span 
class="rm-lmr-10x-x-109">2</span></sup>                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-97-3"  
class="td11">2021</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-97-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-97-5"  
class="td11">•  Wavelet decomposition to detect bright spots followed by motion correction with multiple hypothesis tracking and computing elastic deformation.<br 
class="newline" />•  <a href='https://icy.bioimageanalysis.org/plugin/elastic-motion-correction-concatenation-emc2-of-tracks/' target='_blank'>https://icy.bioimageanalysis.org/plugin/elastic-motion-correction-concatenation-emc2-of-tracks/</a><a 
 id="dx1-1080"></a>                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-97-6"  
class="td11"><a 
href="#Xlagache2021tracking">Lagache et al.</a> <a 
href="#Xlagache2021tracking">2021</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-98-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-98-1"  
class="td11">97  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-98-2"  
class="td11">GraFT                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-98-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-98-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-98-5"  
class="td11">•  Dictionary-based learning of activity traces followed by graph-based segmentation.<br 
class="newline" />•  <a href='https://github.com/adamshch/GraFT-analysis' target='_blank'>https://github.com/adamshch/GraFT-analysis</a><a 
 id="dx1-1081"></a>                                                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-98-6"  
class="td11"><a 
href="#Xcharles2022graft">Charles et al.</a> <a 
href="#Xcharles2022graft">2022</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-99-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-99-1"  
class="td11">98  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-99-2"  
class="td11">CaPTure                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-99-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-99-4"  
class="td11">Analysis pipeline         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-99-5"  
class="td11">•  Binary/watershed segmentation followed by ROI-based mean traces.<br 
class="newline" />•  <a href='https://github.com/LieberInstitute/CaPTure' target='_blank'>https://github.com/LieberInstitute/CaPTure</a><a 
 id="dx1-1082"></a>                                                                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-99-6"  
class="td11"><a 
href="#Xtippani2022capture">Tippani et al.</a> <a 
href="#Xtippani2022capture">2022</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-100-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-100-1"  
class="td11">99  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-100-2"  
class="td11">SpecSeg                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-100-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-100-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-100-5"  
class="td11">•  Cross spectral power-based segmentation of neurons and neurites.<br 
class="newline" />•  <a href='https://github.com/Leveltlab/SpectralSegmentation' target='_blank'>https://github.com/Leveltlab/SpectralSegmentation</a><a 
 id="dx1-1083"></a>                                                                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-100-6"  
class="td11"><a 
href="#Xde2022specseg">de Kraker et al.</a> <a 
href="#Xde2022specseg">2022</a>                                                             </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-101-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-101-1"  
class="td11">100</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-101-2"  
class="td11">CITE-On                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-101-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-101-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-101-5"  
class="td11">•  Online cell detection and trace extraction using CNNs.<br 
class="newline" />•  <a href='https://gitlab.iit.it/fellin-public/cite-on' target='_blank'>https://gitlab.iit.it/fellin-public/cite-on</a><a 
 id="dx1-1084"></a>                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-101-6"  
class="td11"><a 
href="#Xsita2022deep">Sità et al.</a> <a 
href="#Xsita2022deep">2022</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-102-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-102-1"  
class="td11">101</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-102-2"  
class="td11">DL-assisted 2P fiberscope</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-102-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-102-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-102-5"  
class="td11">•  Denoising 2P fiberscope data using deep neural network (conditional generative adversarial network).<br 
class="newline" />•  <a href='https://figshare.com/articles/dataset/Data/19193792' target='_blank'>https://figshare.com/articles/dataset/Data/19193792</a><a 
 id="dx1-1085"></a>                                              </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-102-6"  
class="td11"><a 
href="#Xguan2022deep">Guan et al.</a> <a 
href="#Xguan2022deep">2022</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-103-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-103-1"  
class="td11">102</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-103-2"  
class="td11">4SM                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-103-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-103-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-103-5"  
class="td11">•  Generative adversarial network for image segmentation.<br 
class="newline" />•  <a href='https://github.com/SharifAmit/4SM' target='_blank'>https://github.com/SharifAmit/4SM</a><a 
 id="dx1-1086"></a>                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-103-6"  
class="td11"><a 
href="#Xkamran2022new">Kamran et al.</a> <a 
href="#Xkamran2022new">2022</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-104-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-104-1"  
class="td11">103</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-104-2"  
class="td11">DeepCAD-RT               </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-104-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-104-4"  
class="td11">Denoising                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-104-5"  
class="td11">•  Improved version of DeepCAD for real time performance.<br 
class="newline" />•  <a href='https://github.com/cabooster/DeepCAD-RT/' target='_blank'>https://github.com/cabooster/DeepCAD-RT/</a><a 
 id="dx1-1087"></a>                                                                           </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-104-6"  
class="td11"><a 
href="#Xli2023real">Li et al.</a> <a 
href="#Xli2023real">2023a</a>                                                                      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-105-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-105-1"  
class="td11">104</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-105-2"  
class="td11">SEUDO                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-105-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-105-4"  
class="td11">Trace analysis             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-105-5"  
class="td11">•  Mixture of Gaussians + maximum likelihood; post-hoc activity trace correction.<br 
class="newline" />•  <a href='https://github.com/adamshch/SEUDO' target='_blank'>https://github.com/adamshch/SEUDO</a><a 
 id="dx1-1088"></a>                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-105-6"  
class="td11"><a 
href="#Xgauthier2022detecting">Gauthier et al.</a> <a 
href="#Xgauthier2022detecting">2022</a>                                                               </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-106-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-106-1"  
class="td11">105</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-106-2"  
class="td11">AxialMotionCorrect        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-106-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-106-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-106-5"  
class="td11">•  Axial motion correction via multi-plane scanning plus maximum likelihood optimization.<br 
class="newline" />•  <a href='https://gitlab.com/anflores/axial_motion_correction' target='_blank'>https://gitlab.com/anflores/axial_motion_correction</a><a 
 id="dx1-1089"></a>                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-106-6"  
class="td11"><a 
href="#Xflores2022axial">Flores-Valle and Seelig</a> <a 
href="#Xflores2022axial">2022</a>                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-107-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-107-1"  
class="td11">106</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-107-2"  
class="td11">FIFER                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-107-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-107-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-107-5"  
class="td11">•  Feature-based motion correction, finding features using a density-based estimating and clustering algorithm and matching features with a similarity metric for registration.<br 
class="newline" />•  <a href='https://github.com/Weiyi-Liu-Unique/FIFER' target='_blank'>https://github.com/Weiyi-Liu-Unique/FIFER</a><a 
 id="dx1-1090"></a></td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-107-6"  
class="td11"><a 
href="#Xliu2022fast">Liu et al.</a> <a 
href="#Xliu2022fast">2022</a>                                                                      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-108-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-108-1"  
class="td11">107</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-108-2"  
class="td11">NWB                          </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-108-3"  
class="td11">2022</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-108-4"  
class="td11">Data handling            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-108-5"  
class="td11">•  Neurodata Without Borders (NWB) to standardize ephys and imaging data across tools.<br 
class="newline" />•  <a href='https://github.com/NeurodataWithoutBorders' target='_blank'>https://github.com/NeurodataWithoutBorders</a><a 
 id="dx1-1091"></a>                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-108-6"  
class="td11"><a 
href="#Xrubel2022neurodata">Rübel et al.</a> <a 
href="#Xrubel2022neurodata">2022</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-109-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-109-1"  
class="td11">108</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-109-2"  
class="td11">DeCalciOn                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-109-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-109-4"  
class="td11">Online analysis pipeline</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-109-5"  
class="td11">•  Integrate hardware and software to online decode calcium signals.<br 
class="newline" />•  <a href='https://github.com/zhe-ch/ACTEV' target='_blank'>https://github.com/zhe-ch/ACTEV</a><a 
 id="dx1-1092"></a>                                                                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-109-6"  
class="td11"><a 
href="#Xchen2023hardware">Chen et al.</a> <a 
href="#Xchen2023hardware">2023</a>                                                                   </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-110-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-110-1"  
class="td11">109</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-110-2"  
class="td11">jGCaMP8                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-110-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-110-4"  
class="td11">Calcium indicator        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-110-5"  
class="td11">•  Improved calcium indicators with increased sensitivity and reduced background.                                                                                                                            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-110-6"  
class="td11"><a 
href="#Xzhang2023fast">Zhang et al.</a> <a 
href="#Xzhang2023fast">2023a</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-111-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-111-1"  
class="td11">110</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-111-2"  
class="td11">NeuroSeg-II                  </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-111-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-111-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-111-5"  
class="td11">•  2P cell segmentation using region-based convolutional neural network with modifications.<br 
class="newline" />•  <a href='https://github.com/XZH-James/NeuroSeg2' target='_blank'>https://github.com/XZH-James/NeuroSeg2</a><a 
 id="dx1-1093"></a>                                                      </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-111-6"  
class="td11"><a 
href="#Xxu2023neuroseg">Xu et al.</a> <a 
href="#Xxu2023neuroseg">2023</a>                                                                      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-112-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-112-1"  
class="td11">111</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-112-2"  
class="td11">CaliAli                         </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-112-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-112-4"  
class="td11">Cross-session alignment</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-112-5"  
class="td11">•  Cross-session alignment using vasculature information.<br 
class="newline" />•  <a href='https://github.com/CaliAli-PV/CaliAli' target='_blank'>https://github.com/CaliAli-PV/CaliAli</a><a 
 id="dx1-1094"></a>                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-112-6"  
class="td11"><a 
href="#Xvergara2023caliali">Vergara et al.</a> <a 
href="#Xvergara2023caliali">2023</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-113-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-113-1"  
class="td11">112</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-113-2"  
class="td11">DeepWonder                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-113-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-113-4"  
class="td11">Cell extraction            </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-113-5"  
class="td11">•  Deep-learning-based cell finding for widefield datasets.<br 
class="newline" />•  <a href='https://github.com/yuanlong-o/Deep_widefield_cal_inferece' target='_blank'>https://github.com/yuanlong-o/Deep_widefield_cal_inferece</a><a 
 id="dx1-1095"></a>                                                                             </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-113-6"  
class="td11"><a 
href="#Xzhang2023rapid">Zhang et al.</a> <a 
href="#Xzhang2023rapid">2023b</a>                                                                </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-114-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-114-1"  
class="td11">113</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-114-2"  
class="td11">ASTRA                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-114-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-114-4"  
class="td11">Cell segmentation        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-114-5"  
class="td11">•  Deep neural network for astrocyte segmentation.<br 
class="newline" />•  <a href='https://gitlab.iit.it/fellin-public/astra' target='_blank'>https://gitlab.iit.it/fellin-public/astra</a><a 
 id="dx1-1096"></a>                                                                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-114-6"  
class="td11"><a 
href="#Xbonato2023astra">Bonato et al.</a> <a 
href="#Xbonato2023astra">2023</a>                                                                 </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-115-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-115-1"  
class="td11">114</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-115-2"  
class="td11">SRDTrans                    </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-115-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-115-4"  
class="td11">Denoise                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-115-5"  
class="td11">•  Spatial redundancy for training followed by spatiotemporal transformer architecture to reduce CNN bias/issues.<br 
class="newline" />•  <a href='https://github.com/cabooster/SRDTrans' target='_blank'>https://github.com/cabooster/SRDTrans</a><a 
 id="dx1-1097"></a>                                       </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-115-6"  
class="td11"><a 
href="#Xli2023spatial">Li et al.</a> <a 
href="#Xli2023spatial">2023b</a>                                                                      </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-116-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-116-1"  
class="td11">115</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-116-2"  
class="td11">REALS                        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-116-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-116-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-116-5"  
class="td11">•  Motion correction via simultaneous transformation and low rank and sparse decomposition with gradient-based updates.<br 
class="newline" />•  <a href='https://openaccess.thecvf.com/content/WACV2023/supplemental/Cho_Robust_and_Efficient_WACV_2023_supplemental.zip' target='_blank'>https://openaccess.thecvf.com/content/WACV2023/supplemental/Cho_Robust_and_Efficient_WACV_2023_supplemental.zip</a><a 
 id="dx1-1098"></a>                                 </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-116-6"  
class="td11"><a 
href="#Xcho2023robust">Cho et al.</a> <a 
href="#Xcho2023robust">2023</a>                                                                     </td>
</tr><tr  
 style="vertical-align:baseline;" id="TBL-1-117-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-117-1"  
class="td11">116</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-117-2"  
class="td11"><span 
class="rm-lmbx-12">LD-MCM                </span></td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-117-3"  
class="td11">2023</td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-117-4"  
class="td11">Motion correction        </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-117-5"  
class="td11">•  Motion correction using deep learning feature identification and control point registration.<br 
class="newline" />•  <a href='https://github.com/bahanonu/ciatah' target='_blank'>https://github.com/bahanonu/ciatah</a><a 
 id="dx1-1099"></a>                                                     </td><td  style="white-space:nowrap; text-align:left;" id="TBL-1-117-6"  
class="td11"><a 
href="#Xahanonu2023long">Ahanonu et al.</a> <a 
href="#Xahanonu2023long">2023</a>                                                              </td>
</tr><tr 
class="hline"><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td><td><hr /></td></tr><tr  
 style="vertical-align:baseline;" id="TBL-1-118-"><td  style="white-space:nowrap; text-align:left;" id="TBL-1-118-1"  
class="td11">   </td></tr></table>                                                                     

                                                                          
</div><span class="copyright">&copy;</span> Biafra Ahanonu 2018-2023.
                                                                          

                                                                          
   </figure>
   </div>
<!--l. 68--><p class="indent" >   <hr class='headingsep'>
                                                                          

                                                                          
</p><!--l. 73--><p class="indent" >   <a 
 id="likesection.1"></a><a 
 id="Q1-1-3"></a>
                                                                          

                                                                          
</p>
   <h2 class="likechapterHead"><a 
 id="x1-2000"></a>References</h2>
  <div class="thebibliography">
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xreddy1996fft"></a><span class="bibsp">   </span></span>B Srinivasa Reddy and Biswanath N Chatterji.  An fft-based technique
  for  translation,  rotation,  and  scale-invariant  image  registration.   <span 
class="rm-lmri-12">IEEE</span>
  <span 
class="rm-lmri-12">transactions on image processing</span>, 5(8):1266–1271, 1996.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xthevenaz1998pyramid"></a><span class="bibsp">   </span></span>Philippe Thevenaz, Urs E Ruttimann, and Michael Unser.  A pyramid
  approach to subpixel registration based on intensity.  <span 
class="rm-lmri-12">Image Processing,</span>
  <span 
class="rm-lmri-12">IEEE Transactions on</span>, 7(1):27–41, 1998.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xforoosh2002extension"></a><span class="bibsp">   </span></span>Hassan Foroosh, Josiane B Zerubia, and Marc Berthod.  Extension of
  phase correlation to subpixel registration.  <span 
class="rm-lmri-12">IEEE transactions on image</span>
  <span 
class="rm-lmri-12">processing</span>, 11(3):188–200, 2002.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XKerr2005"></a><span class="bibsp">   </span></span>J N Kerr, D Greenberg, and F Helmchen.  Imaging input and output
  of  neocortical  networks  in  vivo.   <span 
class="rm-lmri-12">Proc Natl Acad Sci U S A</span>,  102(39):
  14063–14068, 2005. ISSN 0027-8424 (Print) 0027-8424. doi: 10.1073/pnas.
  0506029102.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XKuchibhotla2014"></a><span class="bibsp">   </span></span>K V                Kuchibhotla,                S Wegmann,                K J
  Kopeikina, J Hawkes, N Rudinskiy, M L Andermann, T L Spires-Jones,
  B J Bacskai, and B T Hyman. Neurofibrillary tangle-bearing neurons are
  functionally integrated in cortical circuits in vivo. <span 
class="rm-lmri-12">Proc Natl Acad Sci U S</span>
  <span 
class="rm-lmri-12">A</span>, 111(1):510–514, 2014. ISSN 0027-8424. doi: 10.1073/pnas.1318807111.
                                                                          

                                                                          
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XPeron2015"></a><span class="bibsp">   </span></span>Simon P. Peron, Jeremy Freeman, Vijay Iyer, Caiying Guo, and Karel
  Svoboda.                                  A            Cellular            Resolution
  Map of Barrel Cortex Activity during Tactile Behavior.  <span 
class="rm-lmri-12">Neuron</span>, 86(3):
  783–799, 2015.  ISSN 10974199.  doi: 10.1016/j.neuron.2015.03.027.  URL
  <a 
href="http://dx.doi.org/10.1016/j.neuron.2015.03.027" class="url" ><span 
class="rm-lmtt-12">http://dx.doi.org/10.1016/j.neuron.2015.03.027</span></a>.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcarpenter2006cellprofiler"></a><span class="bibsp">   </span></span>Anne E  Carpenter,  Thouis R  Jones,  Michael R  Lamprecht,  Colin
  Clarke, In Han Kang, Ola Friman, David A Guertin, Joo Han Chang,
  Robert A  Lindquist,  Jason  Moffat,  et al.   Cellprofiler:  image  analysis
  software for identifying and quantifying cell phenotypes. <span 
class="rm-lmri-12">Genome biology</span>,
  7(10):1–11, 2006.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmcquin2018cellprofiler"></a><span class="bibsp">   </span></span>Claire McQuin, Allen Goodman, Vasiliy Chernyshev, Lee Kamentsky,
  Beth A Cimini, Kyle W Karhohs, Minh Doan, Liya Ding, Susanne M
  Rafelski, Derek Thirstrup, et al.  Cellprofiler 3.0: Next-generation image
  processing for biology. <span 
class="rm-lmri-12">PLoS biology</span>, 16(7):e2005970, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlamprecht2007cellprofiler"></a><span class="bibsp">   </span></span>Michael R  Lamprecht,  David M  Sabatini,  and  Anne E  Carpenter.
  Cellprofiler™:  free,  versatile  software  for  automated  biological  image
  analysis. <span 
class="rm-lmri-12">Biotechniques</span>, 42(1):71–75, 2007.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmukamel2009automated"></a><span class="bibsp">   </span></span>Eran A Mukamel, Axel Nimmerjahn, and Mark J Schnitzer. Automated
  analysis of cellular signals from large-scale calcium imaging data. <span 
class="rm-lmri-12">Neuron</span>,
  63(6):747–760, 2009.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xavants2009advanced"></a><span class="bibsp">   </span></span>Brian B   Avants,   Nick   Tustison,   Gang   Song,   et al.      Advanced
  normalization tools (ants). <span 
class="rm-lmri-12">Insight j</span>, 2(365):1–35, 2009.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xklein2009elastix"></a><span class="bibsp">   </span></span>Stefan  Klein,  Marius  Staring,  Keelin  Murphy,  Max A  Viergever,  and
                                                                          

                                                                          
  Josien PW Pluim.  Elastix: a toolbox for intensity-based medical image
  registration. <span 
class="rm-lmri-12">IEEE transactions on medical imaging</span>, 29(1):196–205, 2009.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgreenberg2009automated"></a><span class="bibsp">   </span></span>David S Greenberg and Jason ND Kerr.  Automated correction of fast
  motion artifacts for two-photon imaging of awake animals.   <span 
class="rm-lmri-12">Journal of</span>
  <span 
class="rm-lmri-12">neuroscience methods</span>, 176(1):1–15, 2009.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XMiri2011"></a><span class="bibsp">   </span></span>A Miri,                                                                          K Daie,
  R D Burdine, E Aksay, and D W Tank.  Regression-based identification
  of behavior-encoding neurons during large-scale optical imaging of neural
  activity at cellular resolution. <span 
class="rm-lmri-12">J Neurophysiol</span>, 105(2):964–980, 2011. ISSN
  1522-1598 (Electronic) 0022-3077 (Linking).  doi: 10.1152/jn.00702.2010.
  URL <a 
href="http://www.ncbi.nlm.nih.gov/pubmed/21084686" class="url" ><span 
class="rm-lmtt-12">http://www.ncbi.nlm.nih.gov/pubmed/21084686</span></a>.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xbauch2011openbis"></a><span class="bibsp">   </span></span>Angela  Bauch,  Izabela  Adamczyk,  Piotr  Buczek,  Franz-Josef  Elmer,
  Kaloyan  Enimanev,  Pawel  Glyzewski,  Manuel  Kohler,  Tomasz  Pylak,
  Andreas Quandt, Chandrasekhar Ramakrishnan, et al. openbis: a flexible
  framework for managing and analyzing complex data in biology research.
  <span 
class="rm-lmri-12">BMC bioinformatics</span>, 12(1):1–19, 2011.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XFrancis2012"></a><span class="bibsp">   </span></span>M Francis, X Qian, C Charbel, J Ledoux, J C Parker, and M S Taylor.
  Automated region of interest analysis of dynamic Ca(2)+ signals in image
  sequences.   <span 
class="rm-lmri-12">Am  J  Physiol  Cell  Physiol</span>,  303(3):C236–43,  2012.   ISSN
  0363-6143. doi: 10.1152/ajpcell.00016.2012.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xallan2012omero"></a><span class="bibsp">   </span></span>Chris Allan, Jean-Marie Burel, Josh Moore, Colin Blackburn, Melissa
  Linkert,  Scott  Loynton,  Donald  MacDonald,  William J  Moore,  Carlos
  Neves,  Andrew  Patterson,  et al.    Omero:  flexible,  model-driven  data
  management for experimental biology. <span 
class="rm-lmri-12">Nature methods</span>, 9(3):245–253, 2012.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xdiego2013automated"></a><span class="bibsp">   </span></span>Ferran Diego, Susanne Reichinnek, Martin Both, and Fred A Hamprecht.
                                                                          

                                                                          
  Automated identification of neuronal activity from calcium imaging by
  sparse dictionary learning. In <span 
class="rm-lmri-12">Biomedical Imaging (ISBI), 2013 IEEE 10th</span>
  <span 
class="rm-lmri-12">International Symposium on</span>, pages 1058–1061. IEEE, 2013.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtomek2013two"></a><span class="bibsp">   </span></span>Jakub Tomek, Ondrej Novak, and Josef Syka. Two-photon processor and
  seneca: a freely available software package to process data from two-photon
  calcium imaging at speeds down to several milliseconds per frame. <span 
class="rm-lmri-12">Journal</span>
  <span 
class="rm-lmri-12">of neurophysiology</span>, 110(1):243–256, 2013.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xpnevmatikakis2014structured"></a><span class="bibsp">   </span></span>Eftychios A Pnevmatikakis, Yuanjun Gao, Daniel Soudry, David Pfau,
  Clay Lacefield, Kira Poskanzer, Randy Bruno, Rafael Yuste, and Liam
  Paninski.   A  structured  matrix  factorization  framework  for  large  scale
  calcium imaging data analysis. <span 
class="rm-lmri-12">arXiv preprint arXiv:1409.2903</span>, 2014.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XMaruyama2014"></a><span class="bibsp">   </span></span>Ryuichi  Maruyama,  Kazuma  Maeda,  Hajime  Moroda,  Ichiro  Kato,
  Masashi Inoue, Hiroyoshi Miyakawa, and Toru Aonishi.  Detecting cells
  using non-negative matrix factorization on calcium imaging data.  <span 
class="rm-lmri-12">Neural</span>
  <span 
class="rm-lmri-12">Netw</span>, 55:11–19, mar 2014.  ISSN 0893-6080.  doi: 10.1016/j.neunet.2014.
  03.007. URL <a 
href="http://www.ncbi.nlm.nih.gov/pubmed/24705544" class="url" ><span 
class="rm-lmtt-12">http://www.ncbi.nlm.nih.gov/pubmed/24705544</span></a>.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XKaifosh2014"></a><span class="bibsp">   </span></span>Patrick Kaifosh, Jeffrey D Zaremba, Nathan B Danielson, and Attila
  Losonczy.  SIMA: Python software for analysis of dynamic fluorescence
  imaging data. <span 
class="rm-lmri-12">Frontiers in neuroinformatics</span>, 8:80, 2014.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xyatsenko2015datajoint"></a><span class="bibsp">   </span></span>Dimitri Yatsenko, Jacob Reimer, Alexander S Ecker, Edgar Y Walker,
  Fabian  Sinz,  Philipp  Berens,  Andreas  Hoenselaar,  R James  Cotton,
  Athanassios S Siapas, and Andreas S Tolias.   Datajoint: managing big
  scientific data using matlab or python. <span 
class="rm-lmri-12">BioRxiv</span>, page 031658, 2015.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XTeeters2015"></a><span class="bibsp">   </span></span>Jeffery L  Teeters,  Keith  Godfrey,  Rob  Young,  Chinh  Dang,  Claudia
  Friedsam, Barry Wark, Hiroki Asari, Simon Peron, Nuo Li, and Adrien
                                                                          

                                                                          
  Peyrache. Neurodata without borders: creating a common data format for
  neurophysiology. <span 
class="rm-lmri-12">Neuron</span>, 88(4):629–634, 2015.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xpachitariu2016suite2p"></a><span class="bibsp">   </span></span>Marius Pachitariu, Carsen Stringer, Sylvia Schröder, Mario Dipoppa,
  L Federico Rossi, Matteo Carandini, and Kenneth D Harris.   Suite2p:
  beyond 10,000 neurons with standard two-photon microscopy.   <span 
class="rm-lmri-12">Biorxiv</span>,
  page 061507, 2016.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xpnevmatikakis2016simultaneous"></a><span class="bibsp">   </span></span>Eftychios A Pnevmatikakis, Daniel Soudry, Yuanjun Gao, Timothy A
  Machado,  Josh  Merel,  David  Pfau,  Thomas  Reardon,  Yu Mu,  Clay
  Lacefield, Weijian Yang, et al. Simultaneous denoising, deconvolution, and
  demixing of calcium imaging data. <span 
class="rm-lmri-12">Neuron</span>, 89(2):285–299, 2016.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xzhou2016efficient"></a><span class="bibsp">   </span></span>P Zhou, SL Resendez, GD Stuber, RE Kass, and L Paninski. Efficient
  and accurate extraction of in vivo calcium signals from microendoscope
  video data. <span 
class="rm-lmri-12">arXiv preprint arXiv:1605.07266</span>, 2016.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xzhou2018efficient"></a><span class="bibsp">   </span></span>Pengcheng  Zhou,  Shanna L  Resendez,  Jose  Rodriguez-Romaguera,
  Jessica C  Jimenez,  Shay Q  Neufeld,  Andrea  Giovannucci,  Johannes
  Friedrich,  Eftychios A  Pnevmatikakis,  Garret D  Stuber,  Rene  Hen,
  et al.  Efficient and accurate extraction of in vivo calcium signals from
  microendoscopic video data. <span 
class="rm-lmri-12">ELife</span>, 7:e28728, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xapthorpe2016automatic"></a><span class="bibsp">   </span></span>Noah  Apthorpe,  Alexander  Riordan,  Robert  Aguilar,  Jan  Homann,
  Yi Gu, David Tank, and H Sebastian Seung. Automatic neuron detection
  in calcium imaging data using convolutional networks.   In <span 
class="rm-lmri-12">Advances in</span>
  <span 
class="rm-lmri-12">Neural Information Processing Systems</span>, pages 3270–3278, 2016.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xdubbs2016moco"></a><span class="bibsp">   </span></span>Alexander Dubbs, James Guevara, and Rafael Yuste. moco: Fast motion
  correction for calcium imaging. <span 
class="rm-lmri-12">Frontiers in neuroinformatics</span>, 10:6, 2016.
                                                                          

                                                                          
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmaree2016collaborative"></a><span class="bibsp">   </span></span>Raphaël Marée, Loïc Rollus, Benjamin Stévens, Renaud Hoyoux,
  Gilles Louppe, Rémy Vandaele, Jean-Michel Begon, Philipp Kainz, Pierre
  Geurts, and Louis Wehenkel.   Collaborative analysis of multi-gigapixel
  imaging data using cytomine. <span 
class="rm-lmri-12">Bioinformatics</span>, 32(9):1395–1401, 2016.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmohammed2016integrative"></a><span class="bibsp">   </span></span>Ali I Mohammed, Howard J Gritton, Hua-an Tseng, Mark E Bucklin,
  Zhaojie Yao, and Xue Han. An integrative approach for analyzing hundreds
  of  neurons  in  task  performing  mice  using  wide-field  calcium  imaging.
  <span 
class="rm-lmri-12">Scientific reports</span>, 6(1):20986, 2016.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XAhanonu2018sfnposter"></a><span class="bibsp">   </span></span>B. Ahanonu,  L. J.  Kitch,  T. H.  Kim,  M. C.  Larkin,  E. O.  Hamel,
  J. Lecoq, D. E. Aldarondo, and M. J. Schnitzer. Maximum likelihood and
  machine learning based methods for automated cell sorting of large-scale
  neural  calcium  imaging  data.    Society  for  Neuroscience,  2018.    URL
  <a 
href="https://abstractsonline.com/pp8/#!/4649/presentation/41917" class="url" ><span 
class="rm-lmtt-12">https://abstractsonline.com/pp8/#!/4649/presentation/41917</span></a>.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XAhanonu2017sfnposter"></a><span class="bibsp">   </span></span>B. Ahanonu,     L. J.     Kitch,     T. H.     Kim,     M. C.     Larkin,
  E. O.    Hamel,    J. Lecoq,    and    M. J.    Schnitzer.          Maximum
  likelihood    based    cell    sorting    of    large-scale    neural    calcium
  imaging    data.          Society    for    Neuroscience,    2017.          URL
  <a 
href="http://www.abstractsonline.com/pp8/index.html#!/4376/presentation/18520" class="url" ><span 
class="rm-lmtt-12">http://www.abstractsonline.com/pp8/index.html#!/4376/presentation/18520</span></a>.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xahanonu2018neural"></a><span class="bibsp">   </span></span>Biafra Owowonta  Ahanonu.   <span 
class="rm-lmri-12">Neural Ensemble Dynamics in Behaving</span>
  <span 
class="rm-lmri-12">Animals: Computational Approaches and Applications in Amygdala and</span>
  <span 
class="rm-lmri-12">Striatum</span>. Stanford University, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlu2017seeds"></a><span class="bibsp">   </span></span>Jinghao Lu, Chunyuan Li, and Fan Wang.   Seeds cleansing cnmf for
  spatiotemporal neural signals extraction of miniscope imaging data. <span 
class="rm-lmri-12">arXiv</span>
  <span 
class="rm-lmri-12">preprint arXiv:1704.00793</span>, 2017.
  </p>
                                                                          

                                                                          
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xfriedrich2017fast"></a><span class="bibsp">   </span></span>Johannes Friedrich, Pengcheng Zhou, and Liam Paninski.  Fast online
  deconvolution of calcium imaging data.  <span 
class="rm-lmri-12">PLoS computational biology</span>, 13
  (3):e1005423, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xreynolds2017able"></a><span class="bibsp">   </span></span>Stephanie Reynolds, Therese Abrahamsson, Renaud Schuck, P Jesper
  Sjöström,  Simon R  Schultz,  and  Pier Luigi  Dragotti.     Able:  An
  activity-based level set segmentation algorithm for two-photon calcium
  imaging data. <span 
class="rm-lmri-12">eNeuro</span>, pages ENEURO–0012, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xpetersen2017scalpel"></a><span class="bibsp">   </span></span>Ashley  Petersen,  Noah  Simon,  and  Daniela  Witten.     SCALPEL:
  Extracting  Neurons  from  Calcium  Imaging  Data.   <span 
class="rm-lmri-12">ArXiv e-prints</span>,  art.
  arXiv:1703.06946, March 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xspaen2017hnccorr"></a><span class="bibsp">   </span></span>Quico Spaen, Dorit S Hochbaum, and Roberto Asín-Achá.  Hnccorr:
  A novel combinatorial approach for cell identification in calcium-imaging
  movies. <span 
class="rm-lmri-12">arXiv preprint arXiv:1703.01999</span>, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgiovannucci2017onacid"></a><span class="bibsp">   </span></span>Andrea   Giovannucci,   Johannes   Friedrich,   Matt   Kaufman,   Anne
  Churchland,   Dmitri   Chklovskii,   Liam   Paninski,   and   Eftychios A
  Pnevmatikakis.  Onacid: Online analysis of calcium imaging data in real
  time.    In  <span 
class="rm-lmri-12">Advances  in  Neural  Information  Processing  Systems</span>,  pages
  2381–2391, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xinan2017robust"></a><span class="bibsp">   </span></span>Hakan Inan, Murat A Erdogdu, and Mark Schnitzer. Robust estimation
  of neural signals in calcium imaging.  In <span 
class="rm-lmri-12">Advances in Neural Information</span>
  <span 
class="rm-lmri-12">Processing Systems</span>, pages 2901–2910, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xorlandinetcal"></a><span class="bibsp">   </span></span>JG Orlandi,
  S Fernández-García, A Comella-Bolla, M Masana, G García-Díaz
  Barriga,  M Yaghoubi,  A Kipp,  JM Canals,  MA Colicos,  J Davidsen,
                                                                          

                                                                          
  et al.    Netcal:  An  interactive  platform  for  large-scale,  network  and
  population  dynamics  analysis  of  calcium  imaging  recordings,  zenodo
  (2017).
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xpnevmatikakis2017normcorre"></a><span class="bibsp">   </span></span>Eftychios A Pnevmatikakis and Andrea Giovannucci.   Normcorre: An
  online algorithm for piecewise rigid motion correction of calcium imaging
  data. <span 
class="rm-lmri-12">Journal of neuroscience methods</span>, 291:83–94, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsheintuch2017tracking"></a><span class="bibsp">   </span></span>Liron Sheintuch, Alon Rubin, Noa Brande-Eilat, Nitzan Geva, Noa Sadeh,
  Or Pinchasof, and Yaniv Ziv. Tracking the same neurons across multiple
  days in ca2+ imaging data. <span 
class="rm-lmri-12">Cell reports</span>, 21(4):1102–1115, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xguan2018neuroseg"></a><span class="bibsp">   </span></span>Jiangheng Guan, Jingcheng Li, Shanshan Liang, Ruijie Li, Xingyi Li,
  Xiaozhe  Shi,  Ciyu  Huang,  Jianxiong  Zhang,  Junxia  Pan,  Hongbo  Jia,
  et al.  Neuroseg: automated cell detection and segmentation for in vivo
  two-photon ca 2+ imaging data.  <span 
class="rm-lmri-12">Brain Structure and Function</span>, 223(1):
  519–533, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtakekawa2017automatic"></a><span class="bibsp">   </span></span>Takashi Takekawa, Hirotaka Asai, Noriaki Ohkawa, Masanori Nomoto,
  Reiko Okubo-Suzuki, Khaled Ghandour, Masaaki Sato, Yasunori Hayashi,
  Kaoru Inokuchi, and Tomoki Fukai.  Automatic sorting system for large
  calcium imaging data. <span 
class="rm-lmri-12">bioRxiv</span>, page 215145, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xromano2017integrated"></a><span class="bibsp">   </span></span>Sebastián A  Romano,  Verónica  Pérez-Schuster,  Adrien  Jouary,
  Jonathan Boulanger-Weill, Alessia Candeo, Thomas Pietri, and Germán
  Sumbre. An integrated calcium imaging processing toolbox for the analysis
  of  neuronal  population  dynamics.   <span 
class="rm-lmri-12">PLoS  computational  biology</span>,  13(6):
  e1005526, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xrueckl2017samuroi"></a><span class="bibsp">   </span></span>Martin  Rueckl,  Stephen C  Lenzi,  Laura  Moreno-Velasquez,  Daniel
  Parthier, Dietmar Schmitz, Sten Ruediger, and Friedrich W Johenning.
                                                                          

                                                                          
  Samuroi, a python-based software tool for visualization and analysis of
  dynamic  time  series  imaging  at  multiple  spatial  scales.    <span 
class="rm-lmri-12">Frontiers  in</span>
  <span 
class="rm-lmri-12">neuroinformatics</span>, 11:44, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xfillbrunn2017knime"></a><span class="bibsp">   </span></span>Alexander Fillbrunn, Christian Dietz, Julianus Pfeuffer, René Rahn,
  Gregory A Landrum, and Michael R Berthold.  Knime for reproducible
  cross-domain analysis of life science data.  <span 
class="rm-lmri-12">Journal of biotechnology</span>, 261:
  149–156, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xklibisz2017fast"></a><span class="bibsp">   </span></span>Aleksander Klibisz, Derek Rose, Matthew Eicholtz, Jay Blundon, and
  Stanislav Zakharenko.  Fast, simple calcium imaging segmentation with
  fully convolutional networks. In <span 
class="rm-lmri-12">International Workshop on Deep Learning</span>
  <span 
class="rm-lmri-12">in Medical Image Analysis</span>, pages 285–293. Springer, 2017.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xkeemink2018fissa"></a><span class="bibsp">   </span></span>Sander W Keemink, Scott C Lowe, Janelle MP Pakan, Evelyn Dylda,
  Mark CW Van Rossum, and Nathalie L Rochefort.   Fissa: A neuropil
  decontamination toolbox for calcium imaging signals. <span 
class="rm-lmri-12">Scientific reports</span>, 8
  (1):1–12, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmishne2018automated"></a><span class="bibsp">   </span></span>Gal  Mishne,  Ronald R  Coifman,  Maria  Lavzin,  and  Jackie  Schiller.
  Automated   cellular   structure   extraction   in   biological   images   with
  applications to calcium imaging data. <span 
class="rm-lmri-12">bioRxiv</span>, page 313981, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xbuchanan2018penalized"></a><span class="bibsp">   </span></span>E Kelly Buchanan, Ian Kinsella, Ding Zhou, Rong Zhu, Pengcheng Zhou,
  Felipe Gerhard, John Ferrante, Ying Ma, Sharon Kim, Mohammed Shaik,
  et al.   Penalized matrix decomposition for denoising, compression, and
  improved demixing of functional imaging data. <span 
class="rm-lmri-12">bioRxiv</span>, page 334706, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XLu2018min1pipe"></a><span class="bibsp">   </span></span>Jinghao  Lu,  Chunyuan  Li,  Jonnathan  Singh-Alvarado,  Zhe Charles
  Zhou, Flavio Fröhlich, Richard Mooney, and Fan Wang.  MIN1PIPE: A
                                                                          

                                                                          
  Miniscope 1-Photon-Based Calcium Imaging Signal Extraction Pipeline.
  <span 
class="rm-lmri-12">Cell Reports</span>, 23(12):3673–3684, 2018. ISSN 2211-1247.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XGiovannucci2018"></a><span class="bibsp">   </span></span>Andrea  Giovannucci,  Johannes  Friedrich,  Pat  Gunn,  Jeremie  Kalfon,
  Sue Ann  Koay,  Jiannis  Taxidis,  Farzaneh  Najafi,  Jeffrey L  Gauthier,
  Pengcheng Zhou, and David W Tank.  CaImAn: An open source tool for
  scalable Calcium Imaging data Analysis. <span 
class="rm-lmri-12">bioRxiv</span>, page 339564, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgauthier2018detecting"></a><span class="bibsp">   </span></span>Jeffrey L Gauthier, Sue Ann Koay, Edward H Nieh, David W Tank,
  Jonathan W Pillow, and Adam S Charles. Detecting and correcting false
  transients in calcium imaging. <span 
class="rm-lmri-12">bioRxiv</span>, page 473470, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xshen2018automatic"></a><span class="bibsp">   </span></span>Simon P Shen, Hua-an Tseng, Kyle R Hansen, Ruofan Wu, Howard J
  Gritton, Jennie Si, and Xue Han. Automatic cell segmentation by adaptive
  thresholding (acsat) for large-scale calcium imaging datasets. <span 
class="rm-lmri-12">eneuro</span>, 5(5),
  2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmitani2018real"></a><span class="bibsp">   </span></span>Akinori  Mitani  and  Takaki  Komiyama.     Real-time  processing  of
  two-photon  calcium  imaging  data  including  lateral  motion  artifact
  correction. <span 
class="rm-lmri-12">Frontiers in neuroinformatics</span>, 12:98, 2018.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcorder2019amygdalar"></a><span class="bibsp">   </span></span>Gregory  Corder,  Biafra  Ahanonu,  Benjamin F  Grewe,  Dong  Wang,
  Mark J Schnitzer, and Grégory Scherrer. An amygdalar neural ensemble
  that encodes the unpleasantness of pain. <span 
class="rm-lmri-12">Science</span>, 363(6424):276–281, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xahanonu2022recording"></a><span class="bibsp">   </span></span>Biafra  Ahanonu  and  Gregory  Corder.    Recording  pain-related  brain
  activity in behaving animals using calcium imaging calcium imaging and
  miniature microscopes. In <span 
class="rm-lmri-12">Contemporary Approaches to the Study of Pain:</span>
  <span 
class="rm-lmri-12">From Molecules to Neural Networks</span>, pages 217–276. Springer, 2022.
  </p>
                                                                          

                                                                          
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcharles2019neural"></a><span class="bibsp">   </span></span>Adam S Charles, Alex Song, Jeffrey L Gauthier, Jonathan W Pillow,
  and David W Tank.   Neural anatomy and optical microscopy (naomi)
  simulation for evaluating calcium imaging methods. <span 
class="rm-lmri-12">bioRxiv</span>, page 726174,
  2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xradstake2019calima"></a><span class="bibsp">   </span></span>FDW  Radstake,  EAL  Raaijmakers,  R Luttge,  Svitlana  Zinger,  and
  Jean-Philippe Frimat.  Calima: The semi-automated open-source calcium
  imaging analyzer.  <span 
class="rm-lmri-12">Computer methods and programs in biomedicine</span>, 179:
  104991, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsoltanian2019fast"></a><span class="bibsp">   </span></span>Somayyeh Soltanian-Zadeh, Kaan Sahingur, Sarah Blau, Yiyang Gong,
  and Sina Farsiu. Fast and robust active neuron segmentation in two-photon
  calcium imaging using spatiotemporal deep learning.  <span 
class="rm-lmri-12">Proceedings of the</span>
  <span 
class="rm-lmri-12">National Academy of Sciences</span>, 116(17):8554–8563, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xwang2019accurate"></a><span class="bibsp">   </span></span>Yizhi Wang, Nicole V DelRosso, Trisha V Vaidyanathan, Michelle K
  Cahill,  Michael E  Reitman,  Silvia  Pittolo,  Xuelong  Mi,  Guoqiang  Yu,
  and  Kira E  Poskanzer.     Accurate  quantification  of  astrocyte  and
  neurotransmitter fluorescence dynamics for single-cell and population-level
  physiology. <span 
class="rm-lmri-12">Nature Neuroscience</span>, 22(11):1936–1944, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgiovannucci2019caiman"></a><span class="bibsp">   </span></span>Andrea  Giovannucci,  Johannes  Friedrich,  Pat  Gunn,  Jeremie  Kalfon,
  Brandon L  Brown,  Sue Ann  Koay,  Jiannis  Taxidis,  Farzaneh  Najafi,
  Jeffrey L Gauthier, Pengcheng Zhou, et al.  Caiman an open source tool
  for scalable calcium imaging data analysis. <span 
class="rm-lmri-12">Elife</span>, 8:e38173, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmishne2019learning"></a><span class="bibsp">   </span></span>Gal  Mishne  and  Adam S  Charles.     Learning  spatially-correlated
  temporal dictionaries for calcium imaging.  In <span 
class="rm-lmri-12">ICASSP 2019-2019 IEEE</span>
  <span 
class="rm-lmri-12">International  Conference  on  Acoustics,  Speech  and  Signal  Processing</span>
  <span 
class="rm-lmri-12">(ICASSP)</span>, pages 1065–1069. IEEE, 2019.
  </p>
                                                                          

                                                                          
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xdolev2019segment2p"></a><span class="bibsp">   </span></span>Noah  Dolev,  Lior  Pinkus,  and  Michal  Rivlin-Etzion.     Segment2p:
  Parameter-free  automated  segmentation  of  cellular  fluorescent  signals.
  <span 
class="rm-lmri-12">BioRxiv</span>, page 832188, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xchen2019lanmc"></a><span class="bibsp">   </span></span>Zhe  Chen,  Hugh T  Blair,  and  Jason  Cong.    Lanmc:  Lstm-assisted
  non-rigid  motion  correction  on  fpga  for  calcium  image  stabilization.
  In  <span 
class="rm-lmri-12">Proceedings  of  the  2019  ACM/SIGDA  International  Symposium  on</span>
  <span 
class="rm-lmri-12">Field-Programmable Gate Arrays</span>, pages 104–109, 2019.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xshibue2020deconvolution"></a><span class="bibsp">   </span></span>Ryohei Shibue and Fumiyasu Komaki. Deconvolution of calcium imaging
  data using marked point processes.  <span 
class="rm-lmri-12">PLoS computational biology</span>, 16(3):
  e1007650, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsaxena2020localized"></a><span class="bibsp">   </span></span>Shreya             Saxena,             Ian             Kinsella,             Simon
  Musall,  Sharon H  Kim,  Jozsef  Meszaros,  David N  Thibodeaux,  Carla
  Kim, John Cunningham, Elizabeth MC Hillman, Anne Churchland, et al.
  Localized  semi-nonnegative  matrix  factorization  (locanmf)  of  widefield
  calcium  imaging  data.   <span 
class="rm-lmri-12">PLOS  Computational  Biology</span>,  16(4):e1007791,
  2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcantu2020ezcalcium"></a><span class="bibsp">   </span></span>Daniel A  Cantu,  Bo Wang,  Michael W  Gongwer,  Cynthia X  He,
  Anubhuti  Goel,  Anand  Suresh,  Nazim  Kourdougli,  Erica D  Arroyo,
  William  Zeiger,  and  Carlos  Portera-Cailliau.   Ezcalcium:  Open  source
  toolbox for analysis of calcium imaging data. <span 
class="rm-lmri-12">bioRxiv</span>, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xfriedrich2020online"></a><span class="bibsp">   </span></span>Johannes          Friedrich,          Andrea          Giovannucci,          and
  Eftychios A Pnevmatikakis. Online analysis of microendoscopic 1-photon
  calcium imaging data streams. <span 
class="rm-lmri-12">bioRxiv</span>, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtran2020automated"></a><span class="bibsp">   </span></span>Lina M  Tran,  Andrew J  Mocle,  Adam I  Ramsaran,  Alex D  Jacob,
                                                                          

                                                                          
  Paul W  Frankland,  and  Sheena A  Josselyn.     Automated  curation
  of  cnmf-e-extracted  roi  spatial  footprints  and  calcium  traces  using
  open-source automl tools. <span 
class="rm-lmri-12">bioRxiv</span>, 2020a.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtran2020automated2"></a><span class="bibsp">   </span></span>Lina M  Tran,  Andrew J  Mocle,  Adam I  Ramsaran,  Alexander D
  Jacob, Paul W Frankland, and Sheena A Josselyn.  Automated curation
  of  cnmf-e-extracted  roi  spatial  footprints  and  calcium  traces  using
  open-source automl tools. <span 
class="rm-lmri-12">Frontiers in Neural Circuits</span>, 14:42, 2020b.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlecoq2020removing"></a><span class="bibsp">   </span></span>Jerome  Lecoq,  Michael  Oliver,  Joshua H  Siegle,  Natalia  Orlova,  and
  Christof Koch. Removing independent noise in systems neuroscience data
  using deepinterpolation. <span 
class="rm-lmri-12">bioRxiv</span>, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xrubens2020biaflows"></a><span class="bibsp">   </span></span>Ulysse Rubens, Romain Mormont, Lassi Paavolainen, Volker Bäcker,
  Benjamin  Pavie,  Leandro A  Scholz,  Gino  Michiels,  Martin  Maška,
  Devrim Ünay, Graeme Ball, et al.  Biaflows: A collaborative framework
  to  reproducibly  deploy  and  benchmark  bioimage  analysis  workflows.
  <span 
class="rm-lmri-12">Patterns</span>, 1(3):100040, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcassidy2020frequency"></a><span class="bibsp">   </span></span>Ryan M Cassidy, Alexis G Bavencoffe, Elia R Lopez, Sai S Cheruvu,
  Edgar T  Walters,  Rosa A  Uribe,  Anne Marie  Krachler,  and  Max A
  Odem.   Frequency-independent biological signal identification (fibsi): A
  free program that simplifies intensive analysis of non-stationary time series
  data. <span 
class="rm-lmri-12">bioRxiv</span>, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xalles2021chronic"></a><span class="bibsp">   </span></span>Sascha RA  Alles,  Max A  Odem,  Van B  Lu,  Ryan M  Cassidy,  and
  Peter A  Smith.    Chronic  bdnf  simultaneously  inhibits  and  unmasks
  superficial dorsal horn neuronal activity.   <span 
class="rm-lmri-12">Scientific reports</span>, 11(1):1–14,
  2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xkirschbaum2020disco"></a><span class="bibsp">   </span></span>Elke Kirschbaum, Alberto Bailoni, and Fred A Hamprecht. Disco: deep
                                                                          

                                                                          
  learning, instance segmentation, and correlations for cell segmentation in
  calcium imaging.   In <span 
class="rm-lmri-12">Medical Image Computing and Computer Assisted</span>
  <span 
class="rm-lmri-12">Intervention–MICCAI 2020: 23rd International Conference, Lima, Peru,</span>
  <span 
class="rm-lmri-12">October 4–8, 2020, Proceedings, Part V 23</span>, pages 151–162. Springer, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xdenis2020deepcinac"></a><span class="bibsp">   </span></span>Julien  Denis,  Robin F  Dard,  Eleonora  Quiroli,  Rosa  Cossart,  and
  Michel A Picardo.  Deepcinac: a deep-learning-based python toolbox for
  inferring calcium imaging neuronal activity based on movie visualization.
  <span 
class="rm-lmri-12">eneuro</span>, 7(4), 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlee2020real"></a><span class="bibsp">   </span></span>Yaesop Lee, Jing Xie, Eungjoo Lee, Srijesh Sudarsanan, Da-Ting Lin,
  Rong Chen, and Shuvra S Bhattacharyya. Real-time neuron detection and
  neural signal extraction platform for miniature calcium imaging. <span 
class="rm-lmri-12">Frontiers</span>
  <span 
class="rm-lmri-12">in Computational Neuroscience</span>, 14:43, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtan2020deepbrainseg"></a><span class="bibsp">   </span></span>Chaozhen Tan, Yue Guan, Zhao Feng, Hong Ni, Zoutao Zhang, Zhiguang
  Wang,  Xiangning  Li,  Jing  Yuan,  Hui  Gong,  Qingming  Luo,  et al.
  Deepbrainseg:  Automated  brain  region  segmentation  for  micro-optical
  images with a convolutional neural network. <span 
class="rm-lmri-12">Frontiers in neuroscience</span>, 14:
  179, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgriffiths2020real"></a><span class="bibsp">   </span></span>Victoria A   Griffiths,   Antoine M   Valera,   Joanna YN   Lau,   Hana
  Roš, Thomas J Younts, Bóris Marin, Chiara Baragli, Diccon Coyle,
  Geoffrey J Evans, George Konstantinou, et al.  Real-time 3d movement
  correction for two-photon imaging in behaving animals.  <span 
class="rm-lmri-12">Nature methods</span>,
  17(7):741–748, 2020.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xstringer2021cellpose"></a><span class="bibsp">   </span></span>Carsen Stringer, Tim Wang, Michalis Michaelos, and Marius Pachitariu.
  Cellpose: a generalist algorithm for cellular segmentation. <span 
class="rm-lmri-12">Nature Methods</span>,
  18(1):100–106, 2021.
  </p>
                                                                          

                                                                          
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsong2021neural"></a><span class="bibsp">   </span></span>Alexander Song, Jeff L Gauthier, Jonathan W Pillow, David W Tank,
  and Adam S Charles.  Neural anatomy and optical microscopy (naomi)
  simulation   for   evaluating   calcium   imaging   methods.      <span 
class="rm-lmri-12">Journal  of</span>
  <span 
class="rm-lmri-12">Neuroscience Methods</span>, 358:109173, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xfriedrich2021online"></a><span class="bibsp">   </span></span>Johannes
  Friedrich, Andrea Giovannucci, and Eftychios A Pnevmatikakis.  Online
  analysis of microendoscopic 1-photon calcium imaging data streams. <span 
class="rm-lmri-12">PLoS</span>
  <span 
class="rm-lmri-12">computational biology</span>, 17(1):e1008565, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xinan2021fast"></a><span class="bibsp">   </span></span>Hakan  Inan,  Claudia  Schmuckermair,  Tugce  Tasci,  Biafra  Ahanonu,
  Oscar Hernandez, Jérôme Lecoq, Fatih Dinç, Mark J Wagner, Murat
  Erdogdu,  and  Mark J  Schnitzer.    Fast  and  statistically  robust  cell
  extraction from large-scale neural calcium imaging datasets. <span 
class="rm-lmri-12">bioRxiv</span>, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xdong2021minian"></a><span class="bibsp">   </span></span>Zhe  Dong,  William  Mau,  Yu Susie  Feng,  Zachary T  Pennington,
  Lingxuan  Chen,  Yosif  Zaki,  Kanaka  Rajan,  Tristan  Shuman,  Daniel
  Aharoni, and Denise J Cai.  Minian: An open-source miniscope analysis
  pipeline. <span 
class="rm-lmri-12">bioRxiv</span>, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xkolar2021mesmerize"></a><span class="bibsp">   </span></span>Kushal  Kolar,  Daniel  Dondorp,  Jordi Cornelis  Zwiggelaar,  Jørgen
  Høyer, and Marios Chatzigeorgiou.  Mesmerize: a dynamically adaptable
  user-friendly analysis platform for 2d &#x0026; 3d calcium imaging data. <span 
class="rm-lmri-12">bioRxiv</span>,
  page 840488, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlecoq2021removing"></a><span class="bibsp">   </span></span>Jérôme Lecoq, Michael Oliver, Joshua H Siegle, Natalia Orlova, Peter
  Ledochowitsch,  and  Christof  Koch.    Removing  independent  noise  in
  systems neuroscience data using deepinterpolation. <span 
class="rm-lmri-12">Nature Methods</span>, pages
  1–8, 2021.
  </p>
                                                                          

                                                                          
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xhan2021efficient"></a><span class="bibsp">   </span></span>Seungjae Han, Eun-Seo Cho, Inkyu Park, Kijung Shin, and Young-Gyu
  Yoon. Efficient neural network approximation of robust pca for automated
  analysis of calcium imaging data. In <span 
class="rm-lmri-12">International Conference on Medical</span>
  <span 
class="rm-lmri-12">Image  Computing  and  Computer-Assisted  Intervention</span>,  pages  595–604.
  Springer, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtippani2021capture"></a><span class="bibsp">   </span></span>Madhavi  Tippani,  Elizabeth A  Pattie,  Brittany A  Davis,  Claudia V
  Nguyen,  Yanhong  Wang,  Srinidhi Rao  Sripathy,  Brady J  Maher,  Keri
  Martinowich,  Andrew E  Jaffe,  and  Stephanie Cerceo  Page.   Capture:
  Calcium  peak  toolbox  for  analysis  of  in  vitro  calcium  imaging  data.
  <span 
class="rm-lmri-12">bioRxiv</span>, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xrupprecht2021database"></a><span class="bibsp">   </span></span>Peter  Rupprecht,  Stefano  Carta,  Adrian  Hoffmann,  Mayumi  Echizen,
  Antonin Blot, Alex C Kwan, Yang Dan, Sonja B Hofer, Kazuo Kitamura,
  Fritjof  Helmchen,  et al.    A  database  and  deep  learning  toolbox  for
  noise-optimized, generalized spike inference from calcium imaging. <span 
class="rm-lmri-12">Nature</span>
  <span 
class="rm-lmri-12">Neuroscience</span>, 24(9):1324–1337, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcai2021volpy"></a><span class="bibsp">   </span></span>Changjia Cai, Johannes Friedrich, Amrita Singh, M Hossein Eybposh,
  Eftychios A Pnevmatikakis, Kaspar Podgorski, and Andrea Giovannucci.
  Volpy:  automated  and  scalable  analysis  pipelines  for  voltage  imaging
  datasets. <span 
class="rm-lmri-12">PLoS computational biology</span>, 17(4):e1008806, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xli2021reinforcing"></a><span class="bibsp">   </span></span>Xinyang Li, Guoxun Zhang, Jiamin Wu, Yuanlong Zhang, Zhifeng Zhao,
  Xing Lin, Hui Qiao, Hao Xie, Haoqian Wang, Lu Fang, et al. Reinforcing
  neuron  extraction  and  spike  inference  in  calcium  imaging  using  deep
  self-supervised denoising. <span 
class="rm-lmri-12">Nature Methods</span>, pages 1–6, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xde2021specseg"></a><span class="bibsp">   </span></span>Leander
  de Kraker, Koen Seignette, Premnath Thamizharasu, Bastijn JG van den
  Boom, Ildefonso Ferreira Pica, Ingo Willuhn, Christiaan N Levelt, and
                                                                          

                                                                          
  Chris van der Togt. Specseg: cross spectral power-based segmentation of
  neurons and neurites in chronic calcium imaging datasets. <span 
class="rm-lmri-12">bioRxiv</span>, pages
  2020–10, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgiovannucci2021fiola"></a><span class="bibsp">   </span></span>Andrea Giovannucci, Changjia Cai, Cynthia Dong, Marton Rozsa, and
  Eftychios Pnevmatikakis.  Fiola: An accelerated pipeline for fluorescence
  imaging online analysis. 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="XHattori2021.11.10.468164"></a><span class="bibsp">   </span></span>Ryoma     Hattori     and     Takaki     Komiyama.             Patchwarp:
  Corrections    of    non-uniform    image    distortions    in    two-photon
  calcium    imaging    data    by    patchwork    affine    transformations.
  <span 
class="rm-lmri-12">bioRxiv</span>,    2021.            doi:    10.1101/2021.11.10.468164.            URL
  <a 
href="https://www.biorxiv.org/content/early/2021/11/13/2021.11.10.468164" class="url" ><span 
class="rm-lmtt-12">https://www.biorxiv.org/content/early/2021/11/13/2021.11.10.468164</span></a>.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xzhang2021automated"></a><span class="bibsp">   </span></span>Xiaohui Zhang, Eric C Landsness, Wei Chen, Hanyang Miao, Michelle
  Tang,  Lindsey M  Brier,  Joseph P  Culver,  Jin-Moo  Lee,  and  Mark A
  Anastasio.    Automated  sleep  state  classification  of  wide-field  calcium
  imaging data via multiplex visibility graphs and deep learning. <span 
class="rm-lmri-12">Journal of</span>
  <span 
class="rm-lmri-12">Neuroscience Methods</span>, page 109421, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xflotho2022software"></a><span class="bibsp">   </span></span>Philipp Flotho, Shinobu Nomura, Bernd Kuhn, and Daniel J Strauss.
  Software for non-parametric image registration of 2-photon imaging data.
  <span 
class="rm-lmri-12">Journal of Biophotonics</span>, 15(8):e202100330, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xbao2021segmentation"></a><span class="bibsp">   </span></span>Yijun Bao, Somayyeh Soltanian-Zadeh, Sina Farsiu, and Yiyang Gong.
  Segmentation of neurons from fluorescence calcium recordings beyond real
  time. <span 
class="rm-lmri-12">Nature machine intelligence</span>, 3(7):590–600, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtaniguchi2021open"></a><span class="bibsp">   </span></span>Masaki  Taniguchi,  Taro  Tezuka,  Pablo  Vergara,  Sakthivel  Srinivasan,
  Takuma  Hosokawa,  Yoan  Chérasse,  Toshie  Naoi,  Takeshi  Sakurai,
  and  Masanori  Sakaguchi.   Open-source  software  for  real-time  calcium
                                                                          

                                                                          
  imaging and synchronized neuron firing detection.  In <span 
class="rm-lmri-12">2021 43rd Annual</span>
  <span 
class="rm-lmri-12">International Conference of the IEEE Engineering in Medicine &#x0026; Biology</span>
  <span 
class="rm-lmri-12">Society (EMBC)</span>, pages 2997–3003. IEEE, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xmullen2021automated"></a><span class="bibsp">   </span></span>Brian R Mullen, Sydney C Weiser, Desiderio Ascencio, and James B
  Ackman.  Automated classification of signal sources in mesoscale calcium
  imaging. <span 
class="rm-lmri-12">bioRxiv</span>, pages 2021–02, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xwang2021image"></a><span class="bibsp">   </span></span>Yina  Wang,  Henry  Pinkard,  Emaad  Khwaja,  Shuqin  Zhou,  Laura
  Waller, and Bo Huang.  Image denoising for fluorescence microscopy by
  self-supervised transfer learning. <span 
class="rm-lmri-12">bioRxiv</span>, pages 2021–02, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xlagache2021tracking"></a><span class="bibsp">   </span></span>Thibault  Lagache,  Alison  Hanson,  Jesús E  Pérez-Ortega,  Adrienne
  Fairhall, and Rafael Yuste.  Tracking calcium dynamics from individual
  neurons  in  behaving  animals.    <span 
class="rm-lmri-12">PLOS  Computational  Biology</span>,  17(10):
  e1009432, 2021.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcharles2022graft"></a><span class="bibsp">   </span></span>Adam S Charles, Nathan Cermak, Rifqi O Affan, Benjamin B Scott,
  Jackie Schiller, and Gal Mishne. Graft: graph filtered temporal dictionary
  learning  for  functional  neural  imaging.   <span 
class="rm-lmri-12">IEEE  Transactions  on  Image</span>
  <span 
class="rm-lmri-12">Processing</span>, 31:3509–3524, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xtippani2022capture"></a><span class="bibsp">   </span></span>Madhavi  Tippani,  Elizabeth A  Pattie,  Brittany A  Davis,  Claudia V
  Nguyen,  Yanhong  Wang,  Srinidhi Rao  Sripathy,  Brady J  Maher,  Keri
  Martinowich,  Andrew E  Jaffe,  and  Stephanie Cerceo  Page.   Capture:
  Calcium peaktoolbox for analysis of in vitro calcium imaging data. <span 
class="rm-lmri-12">BMC</span>
  <span 
class="rm-lmri-12">neuroscience</span>, 23(1):71, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xde2022specseg"></a><span class="bibsp">   </span></span>Leander                 de Kraker,                 Koen                 Seignette,
  Premnath Thamizharasu, Bastijn JG van den Boom, Ildefonso Ferreira
  Pica, Ingo Willuhn, Christiaan N Levelt, and Chris van der Togt. Specseg
                                                                          

                                                                          
  is a versatile toolbox that segments neurons and neurites in chronic calcium
  imaging datasets based on low-frequency cross-spectral power. <span 
class="rm-lmri-12">Cell reports</span>
  <span 
class="rm-lmri-12">methods</span>, 2(10), 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xsita2022deep"></a><span class="bibsp">   </span></span>Luca Sità, Marco Brondi, Pedro Lagomarsino de Leon Roig, Sebastiano
  Curreli, Mariangela Panniello, Dania Vecchia, and Tommaso Fellin.   A
  deep-learning approach for online cell identification and trace extraction in
  functional two-photon calcium imaging.  <span 
class="rm-lmri-12">Nature Communications</span>, 13(1):
  1529, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xguan2022deep"></a><span class="bibsp">   </span></span>Honghua  Guan,  Dawei  Li,  Hyeon-cheol  Park,  Ang  Li,  Yuanlei  Yue,
  Yung-Tian A Gau, Ming-Jun Li, Dwight E Bergles, Hui Lu, and Xingde
  Li.  Deep-learning two-photon fiberscopy for video-rate brain imaging in
  freely-behaving mice. <span 
class="rm-lmri-12">Nature communications</span>, 13(1):1534, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xkamran2022new"></a><span class="bibsp">   </span></span>Sharif Amit  Kamran,  Khondker Fariha  Hossain,  Hussein  Moghnieh,
  Sarah Riar, Allison Bartlett, Alireza Tavakkoli, Kenton M Sanders, and
  Salah A Baker.  New open-source software for subcellular segmentation
  and analysis of spatiotemporal fluorescence signals using deep learning.
  <span 
class="rm-lmri-12">Iscience</span>, 25(5), 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xli2023real"></a><span class="bibsp">   </span></span>Xinyang  Li,  Yixin  Li,  Yiliang  Zhou,  Jiamin  Wu,  Zhifeng  Zhao,  Jiaqi
  Fan,  Fei  Deng,  Zhaofa  Wu,  Guihua  Xiao,  Jing  He,  et al.   Real-time
  denoising enables high-sensitivity fluorescence time-lapse imaging beyond
  the shot-noise limit. <span 
class="rm-lmri-12">Nature Biotechnology</span>, 41(2):282–292, 2023a.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xgauthier2022detecting"></a><span class="bibsp">   </span></span>Jeffrey L Gauthier, Sue Ann Koay, Edward H Nieh, David W Tank,
  Jonathan W Pillow, and Adam S Charles. Detecting and correcting false
  transients in calcium imaging. <span 
class="rm-lmri-12">Nature Methods</span>, 19(4):470–478, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xflores2022axial"></a><span class="bibsp">   </span></span>Andres Flores-Valle and Johannes D Seelig.   Axial motion estimation
                                                                          

                                                                          
  and correction for simultaneous multi-plane two-photon calcium imaging.
  <span 
class="rm-lmri-12">Biomedical Optics Express</span>, 13(4):2035–2049, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xliu2022fast"></a><span class="bibsp">   </span></span>Weiyi Liu,  Junxia Pan,  Yuanxu Xu,  Meng Wang,  Hongbo Jia,  Kuan
  Zhang, Xiaowei Chen, Xingyi Li, and Xiang Liao. Fast and accurate motion
  correction for two-photon ca2+ imaging in behaving mice.  <span 
class="rm-lmri-12">Frontiers in</span>
  <span 
class="rm-lmri-12">Neuroinformatics</span>, 16:851188, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xrubel2022neurodata"></a><span class="bibsp">   </span></span>Oliver Rübel, Andrew Tritt, Ryan Ly, Benjamin K Dichter, Satrajit
  Ghosh,  Lawrence  Niu,  Pamela  Baker,  Ivan  Soltesz,  Lydia  Ng,  Karel
  Svoboda,   et al.      The   neurodata   without   borders   ecosystem   for
  neurophysiological data science. <span 
class="rm-lmri-12">Elife</span>, 11:e78362, 2022.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xchen2023hardware"></a><span class="bibsp">   </span></span>Zhe  Chen,  Garrett J  Blair,  Changliang  Guo,  Jim  Zhou,  Juan-Luis
  Romero-Sosa,  Alicia  Izquierdo,  Peyman  Golshani,  Jason  Cong,  Daniel
  Aharoni, and Hugh T Blair. A hardware system for real-time decoding of
  in vivo calcium imaging data. <span 
class="rm-lmri-12">Elife</span>, 12:e78344, 2023.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xzhang2023fast"></a><span class="bibsp">   </span></span>Yan  Zhang,  Márton  Rózsa,  Yajie  Liang,  Daniel  Bushey,  Ziqiang
  Wei, Jihong Zheng, Daniel Reep, Gerard Joey Broussard, Arthur Tsang,
  Getahun Tsegaye, et al.  Fast and sensitive gcamp calcium indicators for
  imaging neural populations. <span 
class="rm-lmri-12">Nature</span>, 615(7954):884–891, 2023a.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xxu2023neuroseg"></a><span class="bibsp">   </span></span>Zhehao Xu, Yukun Wu, Jiangheng Guan, Shanshan Liang, Junxia Pan,
  Meng Wang, Qianshuo Hu, Hongbo Jia, Xiaowei Chen, and Xiang Liao.
  Neuroseg-ii: A deep learning approach for generalized neuron segmentation
  in  two-photon  ca2+  imaging.   <span 
class="rm-lmri-12">Frontiers  in  Cellular  Neuroscience</span>,  17:
  1127847, 2023.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xvergara2023caliali"></a><span class="bibsp">   </span></span>Pablo  Vergara,  Yuteng  Wang,  Sakthivel  Srinivasan,  Yoan  Cherasse,
  Toshie Naoi, Yuki Sugaya, Takeshi Sakurai, Masanobu Kano, and Masanori
                                                                          

                                                                          
  Sakaguchi. The caliali tool for long-term tracking of neuronal population
  dynamics in calcium imaging. <span 
class="rm-lmri-12">bioRxiv</span>, pages 2023–05, 2023.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xzhang2023rapid"></a><span class="bibsp">   </span></span>Yuanlong  Zhang,  Guoxun  Zhang,  Xiaofei  Han,  Jiamin  Wu,  Ziwei  Li,
  Xinyang Li, Guihua Xiao, Hao Xie, Lu Fang, and Qionghai Dai.  Rapid
  detection of neurons in widefield calcium imaging datasets after training
  with synthetic data. <span 
class="rm-lmri-12">Nature Methods</span>, 20(5):747–754, 2023b.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xbonato2023astra"></a><span class="bibsp">   </span></span>Jacopo Bonato, Sebastiano Curreli, Sara Romanzi, Stefano Panzeri, and
  Tommaso  Fellin.   Astra:  a  deep  learning  algorithm  for  fast  semantic
  segmentation of large-scale astrocytic networks.  <span 
class="rm-lmri-12">bioRxiv</span>, pages 2023–05,
  2023.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xli2023spatial"></a><span class="bibsp">   </span></span>Xinyang Li, Xiaowan Hu, Xingye Chen, Jiaqi Fan, Zhifeng Zhao, Jiamin
  Wu, Haoqian Wang, and Qionghai Dai.  Spatial redundancy transformer
  for self-supervised fluorescence image denoising.  <span 
class="rm-lmri-12">bioRxiv</span>, pages 2023–06,
  2023b.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xcho2023robust"></a><span class="bibsp">   </span></span>Junmo Cho, Seungjae Han, Eun-Seo Cho, Kijung Shin, and Young-Gyu
  Yoon.  Robust and efficient alignment of calcium imaging data through
  simultaneous low rank and sparse decomposition.  In <span 
class="rm-lmri-12">Proceedings of the</span>
  <span 
class="rm-lmri-12">IEEE/CVF Winter Conference on Applications of Computer Vision</span>, pages
  1939–1948, 2023.
  </p>
  <p class="bibitem" ><span class="biblabel">
<a 
 id="Xahanonu2023long"></a><span class="bibsp">   </span></span>Biafra Ahanonu, Andrew Crowther, Artur Kania, Mariela Rosa Casillas,
  and Allan Basbaum. Long-term optical imaging of the spinal cord in awake,
  behaving animals. <span 
class="rm-lmri-12">bioRxiv</span>, pages 2023–05, 2023.
</p>
  </div>
<!--l. 91--><p class="indent" >   <hr class='headingsep'>  <hr class='headingsep'> <h3>Footnotes</h3> <a 
 id="Q1-1-5"></a>  </div> </p> 