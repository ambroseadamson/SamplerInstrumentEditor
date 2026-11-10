# Introduction
 
I enjoy music production on mobile devices such as tablets and mobile phones so that I can develop musical ideas whilst travelling rather than waiting to get to my home studio. 

One of the problems I'm having is that I use different music apps on those devices depending how simple or complex the musical idea is and each of the apps that I use  (koala sampler/cubasis/caustic/fl studio mobile), worked with different sampler instrument formats:

- Koala = exported koala song format 
- Cubasis = mini sampler format 
- Caustic/fl studio mobile = soundfont file format 

Neither of the apps so each others instrument formats and require excessive work to migrate the instruments between the apps (essentially recreating those instruments for each app). 

I want to build an android app that:
- imports the sample instrument
- display the imported instrument
  - provide tools to edit the instrument
- export the instrument

  
# Import the instrument

This would support following formats:
- sample banks from the koala song format
- Cubasis MiniSampler format
- Soundfont format (.sf2)

# Display the instrument 

This would provide two instrument views:

- Slice Instrument View 
- Music Instrument View

# Slice Instrument View

This will display the instrument as sliced audio like the audio view in the Recycle App:
<img width="1003" height="895" alt="image" src="https://github.com/user-attachments/assets/4da0bfcd-9a06-41e3-8a62-f093d9ec34f8" />

# Music Instrument View
This will display the instrument in a more traditional manner like Directwave in FL Studio:
<img width="659" height="511" alt="image" src="https://github.com/user-attachments/assets/2690be64-4f50-49be-b6f6-11895c0b6b84" />

# Export the instrument

This would support following formats:
- Cubasis MiniSampler format
- Soundfont format (.sf2)


# Music Instrument View
t convert them into MinisSampler Instrument files used by MiniSampler in Cubasis or take the samples from the banks in an exported koala song, and convert them into MinisSampler Instrument files used by MiniSampler in Cubasis to make it easier my existing instrument libraries for these apps. This libary should be compatible with developing apps in Android and iOS.
