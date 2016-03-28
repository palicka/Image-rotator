# image-rotator
What you can do with image-rotator:
- rotate image with auto-scaling to avoid black triangles in the corners (when displaying to user)
- save rotated and cropped image from original image


##Screenshot

<img src="https://raw.githubusercontent.com/palicka/image-rotator/master/app/src/main/res/drawable/demp.gif" width="448" />


Installation
=======

Add it in your root build.gradle at the end of repositories:

	allprojects {
		repositories {
			...
			maven { url "https://jitpack.io" }
		}
	}

Add the dependency

	dependencies {
		compile 'com.github.palicka:image-rotator:0.1'
	}

License
=======
Copyright 2016, Pavol Fogas 

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
