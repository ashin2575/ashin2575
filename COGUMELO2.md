while true do
   gg.clearResults()
   gg.searchNumber("236700", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1, 0)
   gg.refineNumber("236700", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1, 0)
   gg.refineNumber("236700", gg.TYPE_DOUBLE, false, gg.SIGN_EQUAL, 0, -1, 0)
   gg.getResults(100, nil, nil, nil, nil, nil, nil, nil, nil)
   gg.editAll("999999")
   gg.sleep(300)
end
