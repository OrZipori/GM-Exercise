android_library(
  name = "activities",
  srcs = glob(["src/main/java/com/orzipori/gmexercise/android/activities/*.java"]),
  custom_package = "com.orzipori.gmexercise.android.activities",
  manifest = "src/main/java/com/orzipori/gmexercise/android/activities/AndroidManifest.xml",
  resource_files = glob(["src/main/java/com/orzipori/gmexercise/android/activities/res/**"]),
)

android_binary(
    name = "gmexercise",
    custom_package = "com.orzipori.gmexercise.android.activities",
    manifest = "src/main/java/com/orzipori/gmexercise/android/AndroidManifest.xml",
    resource_files = glob(["src/main/java/com/orzipori/gmexercise/android/res/**"]),
    deps = [":activities"],
)
