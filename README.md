# This is my first step.
Name = c('PSYCHOTHERAPY AND PSYCHOSOMATICS ',
         'NATURE HUMAN BEHAVIOUR',
         'LEADERSHIP QUARTERLY ',
         'JOURNAL OF THE AMERICAN ACADEMY OF CHILD AND ADOLESCENT PSYCHIATRY',
         'JOURNAL OF ORGANIZATIONAL BEHAVIOR',
         'PSYCHOLOGICAL MEDICINE ',
         'JOURNAL OF PERSONALITY AND SOCIAL PSYCHOLOGY',
         'JOURNAL OF APPLIED PSYCHOLOGY ',
         'JOURNAL OF OCCUPATIONAL HEALTH PSYCHOLOGY ',
         'PERSONNEL PSYCHOLOGY ',
         'PSYCHOLOGICAL SCIENCE',
         'COMPUTERS IN HUMAN BEHAVIOR ',
         'CHILD DEVELOPMENT',
         'JOURNAL OF EDUCATIONAL PSYCHOLOGY ',
         '心理学报')
Num = c(97,222,50,340,65,206,159,104,36,79,170,256,145,67,86)
Category = c('PSYCHOLOGY - SCIE ',
             'PSYCHOLOGY, EXPERIMENTAL - SSCI',
             'PSYCHOLOGY, APPLIED - SSCI ',
             'PSYCHOLOGY, DEVELOPMENTAL - SSCI ',
             'PSYCHOLOGY, APPLIED - SSCI ',
             'PSYCHOLOGY - SCIE;PSYCHOLOGY, CLINICAL - SSCI ',
             'PSYCHOLOGY, SOCIAL ',
             'PSYCHOLOGY, APPLIED - SSCI ',
             'PSYCHOLOGY, APPLIED - SSCI',
             'PSYCHOLOGY, APPLIED - SSCI ',
             'PSYCHOLOGY, MULTIDISCIPLINARY - SSCI ',
             'PSYCHOLOGY, EXPERIMENTAL - SSCI;PSYCHOLOGY, MULTIDISCIPLINARY - SSCI ',
             'PSYCHOLOGY, DEVELOPMENTAL - SSCI;PSYCHOLOGY, EDUCATIONAL - SSCI ',
             'PSYCHOLOGY, EDUCATIONAL - SSCI ',
             'PSYCHOLOGY, MULTIDISCIPLINARY - SSCI ')
df <- data.frame(Name,Num,Category)
write.csv(df, file = "C: \ collection",row.names = FALSE)
print(df)
