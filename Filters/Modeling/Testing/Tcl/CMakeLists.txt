if(VTK_DATA_ROOT)
  add_test_tcl(TestImageMarchingCubes Graphics)
  add_test_tcl(TestRibbonAndTube Graphics)
  add_test_tcl(contour2DAll Graphics)
  add_test_tcl(contour3DAll Graphics)
  add_test_tcl(eleState Graphics)
  add_test_tcl(sync3dAll Graphics)
endif()

add_test_tcl(camera Hybrid)
add_test_tcl(extrudeCopyCD Graphics)
add_test_tcl(Hyper Graphics)
add_test_tcl(HyperScalarBar Graphics)
add_test_tcl(KlineBottle Graphics)
add_test_tcl(schwarz Graphics)
add_test_tcl(smoothCyl Graphics)
add_test_tcl(smoothCyl2 Graphics)
add_test_tcl(subdividePointData Graphics)
add_test_tcl(subDivideTetra Graphics)
add_test_tcl(TenEllip Graphics)
add_test_tcl(TestBandedContourFilter Graphics)
add_test_tcl(TestBoxFunction Graphics)
add_test_tcl(TestFillHolesFilter Graphics)
add_test_tcl(TestRuledSurface Graphics)
add_test_tcl(TestRuledSurface2 Graphics)
add_test_tcl(TestSpherePuzzle Graphics)
add_test_tcl(TestSpherePuzzleArrows Graphics)
