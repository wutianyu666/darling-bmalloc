project(bmalloc)

set(CMAKE_CXX_STANDARD 14)

add_darling_static_library(bmalloc FAT
	SOURCES
		bmalloc/Allocator.cpp
		bmalloc/AvailableMemory.cpp
		bmalloc/Cache.cpp
		bmalloc/Deallocator.cpp
		bmalloc/DebugHeap.cpp
		bmalloc/Environment.cpp
		bmalloc/Heap.cpp
		bmalloc/LargeMap.cpp
		bmalloc/Logging.cpp
		bmalloc/ObjectType.cpp
		bmalloc/StaticMutex.cpp
		bmalloc/VMHeap.cpp
		bmalloc/Zone.cpp
)
