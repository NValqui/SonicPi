#Challenge F

num = 21

87.times do
  use_synth :piano
  num = num + 1 #make num bigger
  play num
  sleep 0.5
end

87.times do
  use_synth :piano
  num = num - 1
  play num
  sleep 0.25
end

87.times do
  use_synth :piano
  num = num + 1
  play num
  sleep 0.125
end
