add_executable(pcl_global_classification src/global_classification.cpp)
target_link_libraries(pcl_global_classification pcl_apps pcl_3d_rec_framework pcl_common pcl_io pcl_filters pcl_visualization pcl_segmentation pcl_sample_consensus pcl_surface)

add_executable(pcl_local_or_mian src/local_recognition_mian_dataset.cpp)
target_link_libraries(pcl_local_or_mian pcl_apps pcl_3d_rec_framework pcl_recognition pcl_common pcl_io pcl_filters pcl_visualization pcl_segmentation pcl_sample_consensus pcl_surface pcl_keypoints)

#add_executable(pcl_local_face src/local_recognition_faces.cpp)
#target_link_libraries(pcl_local_face pcl_apps pcl_3d_rec_framework pcl_recognition pcl_common pcl_io pcl_filters pcl_visualization pcl_segmentation pcl_sample_consensus pcl_surface pcl_keypoints)
